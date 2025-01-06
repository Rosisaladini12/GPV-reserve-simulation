# GPV Reserve Calculation Simulation  

This project demonstrates the calculation of insurance reserves for the THT (Savings and Insurance) program at PT XYZ using the Gross Premium Valuation (GPV) method. GPV is a standard actuarial approach to determining the present value of future benefits and expenses minus the present value of future premiums.

---

## **Objective**
The objective of this project is to:  
1. Calculate reserves for insurance programs using the GPV method.
2. Automate the reserve calculation process with Python to improve accuracy and efficiency.
---

## **Key Features**
- **Valuation of Reserves:**  
  Detailed cash flow valuations were performed for various benefits, including pension benefits, death benefits, and costs (variable and fixed). The methodology also accounts for inflows from gross premiums.
  
- **Automation:**  
  Python-based automation was implemented to minimize manual errors and ensure efficient reserve calculations.  

---

## **Methodology**
The GPV method calculates reserves based on:  
1. Present value of benefits and costs (pension benefits, death benefits, fixed/variable costs)
2. Present value of premiums (gross premiums)
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
