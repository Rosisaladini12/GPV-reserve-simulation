# GPV Reserve Calculation Simulation  

This project involves calculating insurance reserves for the THT (Savings and Insurance) program at PT XYZ using the **Gross Premium Valuation (GPV)** method. GPV is a widely adopted actuarial approach that calculates the present value of future benefits and expenses minus the present value of future premiums.

---

## **Objective**
The objective of this project is to:  
1. Calculate the reserves required for insurance programs using the GPV method.  
2. Automate the reserve calculation process through Python.
---

## **Key Features**
- **Valuation of Reserves:**  
  Separate cash inflow valuations were performed for different benefits, including pension benefits, death benefits, and other cost such as variable and fixed cost. Otherwise cash inflow valuation was performed only from gross premium.
  
- **Automation:**  
  Reserve calculations were automated using Python to minimize manual errors and enhance efficiency.  

---

## **Methodology**
The GPV method calculates reserves based on:  
1. Present value of benefits and costs (pension benefits, death benefits, other cost)
2. Present value of premiums (gross premium)
3. Reserve is the difference:  
   Reserve = PV{Benefits} - PV{Premiums}

---

## **Files**
- `script.py`: Python script to automate reserve calculations using the GPV method.  
- `input_data.xlsx`: Contains input data for participant details, program assumptions, and parameters.  

---

## **Tools**
- **Python:** For automating reserve calculations.  

---

## **Results**
The project successfully delivered:  
1. **Automated Reserve Calculation:** A faster and more reliable process using Python.  
2. **Comprehensive Projections:** Detailed financial projections for 2024–2080, including reserves, contributions, and payouts.

---

## **How to Use**
1. Download the repository files (`script.py`, `input_data.xlsx`).  
2. Install Python with the necessary libraries (e.g., pandas, numpy).  
3. Run the Python script:  
   ```bash
   python script.py
