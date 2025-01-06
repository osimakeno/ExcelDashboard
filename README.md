# ExcelDashboard
This project uses a data set from a call center and I am using it to create a performance analysis dashboard. 

Firstly, I transformed and cleaned the data a bit using Excel Power Query

<img width="1440" alt="Screenshot 2025-01-05 at 12 32 37 PM" src="https://github.com/user-attachments/assets/eb2ee52d-66f8-411a-a9c6-2c1896f318c6" />

After making sure all data field are assigned the right data type, I created a new column called days, where I extracted the day number from date field, using the "=DAY()" formular in excel.
This will help in creating a time series since the data is available is for a particular month (October) in one year.

<img width="1440" alt="Screenshot 2025-01-05 at 1 18 47 PM" src="https://github.com/user-attachments/assets/150c0fa6-f195-483c-b883-d0c0d09d17cf" />

Next, I created pivat tables and chart in which I used in creating the dashboard. 
I created 5 different charts, which are:
  1. Line charts for call trend.

   <img width="1440" alt="Screenshot 2025-01-05 at 5 06 53 PM" src="https://github.com/user-attachments/assets/d8f0ba95-5bc3-4b03-825c-1612b7bb40a4" />

  2. Bar chart for the call channels, Pie chart would have been best for this, but the margins where too small.
     
  4. A map for the states.
     <img width="1440" alt="Screenshot 2025-01-05 at 1 55 37 PM" src="https://github.com/user-attachments/assets/777d7f97-8a1f-44ff-b64b-bac918a0597e" />

  6. A column chart for call reason.
     <img width="1440" alt="Screenshot 2025-01-05 at 2 01 06 PM" src="https://github.com/user-attachments/assets/8602405a-4aac-44b2-8421-d869272ddb7d" />

  8. A bar chart for the response time.
     <img width="1440" alt="Screenshot 2025-01-05 at 2 04 45 PM" src="https://github.com/user-attachments/assets/358159dc-235b-4d6d-881a-767cbaba3c27" />
     
  10. A bar chart for the sentiment types.
      <img width="1440" alt="Screenshot 2025-01-05 at 5 11 07 PM" src="https://github.com/user-attachments/assets/3e66c041-8b7f-40e9-bab9-017e078cc597" />



