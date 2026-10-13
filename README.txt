PENSTOCK: HYDRO PLANT WALKDOWNS AND MAINTENANCE (DEMONSTRATION)
================================================================

WHAT THIS IS
A working prototype of operator walkdown (rounds) and maintenance
management (CMMS) software for hydroelectric plants. It is one
self-contained file that runs in any modern web browser (Edge, Chrome,
Firefox, Safari) on a Windows tablet, laptop or phone. SAMPLE DATA ONLY.

HOW TO OPEN IT
1. Unzip this folder.
2. Double-click Penstock_Demo.html. It opens in your web browser.
3. No installation, no login, no internet needed after it opens.

TWO SAMPLE DATA SETS
Go to "Templates and data", choose a set under "Demo data", then
"Load demo data":
 - Nepal run-of-river plants (metric): Upper Khola and Lower Khola HEP.
 - Los Alamos RFI demo (imperial): El Vado and Abiquiu. Values are
   invented, not real plant readings.

WHAT TO TRY
 - Walkdowns > Start walkdown: a reading outside its normal range turns
   red, asks for a note, and creates a work order on submit. Run-hour
   meters cannot go backwards.
 - Trends: a bearing temperature is rising; the app predicts when it
   reaches its limit and offers a predictive work order.
 - Preventive maintenance: tasks by calendar or by RUN HOURS. Run-hour
   tasks use the meter readings from walkdowns to predict the due date
   (for example, bearing oil every 2,500 run hours).
 - Work orders: plan a date, record labor hours, and issue parts from
   stock. Totals of labor and parts cost are kept.
 - Parts and materials: stock per plant, reorder alerts, receive stock.
 - Equipment: open any item for its run hours, readings, recurring tasks
   and full maintenance history.
 - Operator log, search box, Export CSV and Full backup.
 - Templates and data: rename plants, edit checklists, add operators.

WHERE THE DATA IS KEPT
Everything is saved in this browser on this device only. Use "Full
backup (JSON)" to move data and "Restore from a backup file" to load it.

PUTTING IT ON A WEBSITE
Upload Penstock_Demo.html to any web host. Visitors can open it with no
login; each visitor gets a private copy of the sample data.

LIMITATIONS OF THIS PROTOTYPE
 - No central server: users do not yet share one database.
 - No user accounts, MFA, roles or audit log.
 - No photo capture, QR tags, or Ignition connection.
 - The AI handover summary uses simple rules when run from this file.
A production system adds these.

Chart.js 4.4.1 is included under the MIT License (https://www.chartjs.org).
