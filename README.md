# ETF-Project
import pandas as pd
import numpy as np
# Load the data
file_path = r"C:\Users\smart\OneDrive - NJIT\Desktop\etf_data_shriya.csv"
data = pd.read_csv(file_path)
![1 code](https://github.com/Anandshri/ETF-Project/assets/128425487/0e930e05-506c-439a-a366-2f87507a2d0d)
data![code 2](https://github.com/Anandshri/ETF-Project/assets/128425487/0f3d88f5-f171-4f72-bcfe-40909aa15635)
![code 3](https://github.com/Anandshri/ETF-Project/assets/128425487/83fd4735-dda8-47a3-ba7a-f68bc2f83fbe)
![code 4](https://github.com/Anandshri/ETF-Project/assets/128425487/004f962c-55c6-4f63-ad43-cfd61993215f)
data_2 = data[['ETFG_Date', 'As_Of_Date', 'Composite_Ticker', 'shares_outstanding', 'nav', 'fundflow', 'Risk_Total_Score', 'Risk_Volatility', 'Risk_Deviation', 'Risk_Country', 'Risk_Structure', 'Risk_Liquidity', 'Risk_Efficiency', 'Reward_Score','lag_nav','log_ret','fund_flow_p_dummy','fund_flow_N_dummy','DummyA','DummyB','DummyC','DummyD','Dummy12/22/2019']]
data_2.isnull().sum()/len(data_2)
![code 5](https://github.com/Anandshri/ETF-Project/assets/128425487/b2c262b1-53dd-402e-8d4e-94c7373d58a9)
![code 6](https://github.com/Anandshri/ETF-Project/assets/128425487/f63943a8-5268-45ea-8ca4-c2406292136c)
![code 7](https://github.com/Anandshri/ETF-Project/assets/128425487/d0485e7a-341f-4e44-b955-593940d097cc)
![code 8](https://github.com/Anandshri/ETF-Project/assets/128425487/2a5ca722-d8ee-454e-8681-4981a20e5c88)
![code 9](https://github.com/Anandshri/ETF-Project/assets/128425487/09f0d26e-e967-411e-aeaf-5cb31d7d099f)
![code 10](https://github.com/Anandshri/ETF-Project/assets/128425487/5316d9d2-2e87-4091-88db-f0fffc7daae8)
![code 11](https://github.com/Anandshri/ETF-Project/assets/128425487/e4489c3a-68a9-417d-b32d-cb36d82e4e5e)
![code 12](https://github.com/Anandshri/ETF-Project/assets/128425487/4bf5f1ef-53e4-4b91-9ead-2f623a7da0f6)
![code 13](https://github.com/Anandshri/ETF-Project/assets/128425487/f9471448-6ab2-4136-9623-66a0cdfd0cf0)
![code 14](https://github.com/Anandshri/ETF-Project/assets/128425487/2791640a-3404-4cc4-a9e0-dc68cc655cb5)
![code 15](https://github.com/Anandshri/ETF-Project/assets/128425487/53ae98eb-e2e6-42aa-8b55-c52409154782)
![code 16](https://github.com/Anandshri/ETF-Project/assets/128425487/03302d01-2780-4153-9c5e-b18a3283ad25)
