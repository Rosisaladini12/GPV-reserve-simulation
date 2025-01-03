# GPV Reserve Calculation Simulation  

This project involves calculating insurance reserves for the THT (Savings and Insurance) program at PT Taspen using the **Gross Premium Valuation (GPV)** method. GPV is a widely adopted actuarial approach that calculates the present value of future benefits and expenses minus the present value of future premiums.

---

## **Objective**
The objective of this project is to:  
1. Calculate the reserves required for insurance programs using the GPV method.  
2. Automate the reserve calculation process through Python and Excel.  
3. Provide detailed financial insights for better decision-making and program sustainability.

---

## **Key Features**
- **Valuation of Reserves:**  
  Separate valuations were performed for different benefits, including pension benefits, death benefits, and withdrawal benefits.  
- **Automation:**  
  Reserve calculations were automated using Python and Excel to minimize manual errors and enhance efficiency.  

---

## **Methodology**
The GPV method calculates reserves based on:  
1. Present value of benefits and costs:  
   \[
   PV_{Benefits} = \sum_{t=1}^{n} \frac{Benefit_t}{(1+i)^t}
   \]
2. Present value of premiums:  
   \[
   PV_{Premiums} = \sum_{t=1}^{n} \frac{Premium_t}{(1+i)^t}
   \]
3. Reserve is the difference:  
   \[
   Reserve = PV_{Benefits} - PV_{Premiums}
   \]

**Key Assumptions Used:**  
- Interest rate: 9.5%  
- Salary growth rate: 2.5% annually  
- Inflation rate: 5.51%  

---

## **Files**
- `script.py`: Python script to automate reserve calculations using the GPV method.  
- `input_data.xlsx`: Contains input data for participant details, program assumptions, and parameters.  
- `results.xlsx`: Output file detailing reserves and projections.

---

## **Tools**
- **Python:** For automating reserve calculations.  
- **Excel:** For manual calculations and data visualization.

---

## **Results**
The project successfully delivered:  
1. **Automated Reserve Calculation:** A faster and more reliable process using Python.  
2. **Manual Validation in Excel:** Ensuring accuracy through cross-verification.  
3. **Comprehensive Projections:** Detailed financial projections for 2024–2080, including reserves, contributions, and payouts.

---

## **How to Use**
1. Download the repository files (`script.py`, `input_data.xlsx`).  
2. Install Python with the necessary libraries (e.g., pandas, numpy).  
3. Run the Python script:  
   ```bash
   python script.py
