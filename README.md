💻 Laptop Request Catalog Item – ServiceNow
📘 Project Overview

The Laptop Request Catalog Item project streamlines the process of requesting laptops within an organization by leveraging ServiceNow’s Service Catalog module.
Traditionally, employees used manual methods to request laptops, which were slow and error-prone. This project introduces an automated and dynamic catalog form that improves accuracy, speed, and overall employee experience.

🎯 Objective

Design and implement a ServiceNow catalog item that enables employees to:

Submit laptop requests dynamically

Receive clear guidance and form validations

Automatically manage UI behaviors (e.g., showing additional fields dynamically)

Maintain governance and track all configuration changes

🧠 Problem Statement

Employees needed a quick and efficient way to request laptops for work.
The existing manual process caused delays and lacked form validation.
To resolve this, a ServiceNow Service Catalog Item was developed with:

Dynamic fields

Validation logic

Reset functionality

Update set tracking for easy deployment

⚙️ Features

✅ Dynamic Form Fields — Fields like “Accessories Details” appear only when relevant
✅ Form Validation — Ensures correct data entry before submission
✅ Reset Form Action — Allows users to clear all fields instantly
✅ Update Set Management — Supports export/import between instances
✅ Governance Ready — All changes tracked for audit and deployment

🧩 Technologies Used
Technology	Purpose
ServiceNow	Platform for catalog item creation
UI Policies & Actions	Dynamic form behavior and interactivity
UI Scripts	Custom client-side form reset function
Update Sets	Deployment and version control
Tanzu Application Service	Supporting environment setup
UiPath RPA	Workflow automation (optional integration)
🚀 Implementation Milestones
🔹 Milestone 1 – Task Initiation

Created a Local Update Set named Laptop Request.

🔹 Milestone 2 – Catalog Item Creation

Added new Service Catalog Item under Hardware Category.

Configured fields such as:

Laptop Model

Justification

Additional Accessories

Accessories Details

🔹 Milestone 3 – Dynamic UI Policies

Implemented logic to show Accessories Details only if Additional Accessories is checked.

🔹 Milestone 4 – UI Actions

Added Reset Form button using a client script (g_form.clearForm()).

🔹 Milestone 5 – Update Set Export

Exported completed update set to XML for migration.

🔹 Milestone 6 – Deployment

Imported and committed update set on another instance.

🔹 Milestone 7 – Testing

Verified all dynamic and validation functionalities on the target instance.

🧾 Example Script (UI Action)
function resetForm() {
    g_form.clearForm();  // Clears all fields in the form
    alert("The form has been reset.");
}

📊 Results

Reduced laptop request handling time.

Improved form accuracy and data consistency.

Enhanced employee satisfaction through a simple, guided request process.

Demonstrated the use of ServiceNow Catalog Items for digital transformation.

🏁 Conclusion
The Laptop Request Catalog Item Project effectively demonstrates how ServiceNow can replace manual processes with automated, efficient, and user-centric solutions.
It enhances organizational workflow, ensures data accuracy, and provides a scalable model for future service catalog automation.

The Laptop Request Catalog Item Project effectively demonstrates how ServiceNow can replace manual processes with automated, efficient, and user-centric solutions.
It enhances organizational workflow, ensures data accuracy, and provides a scalable model for future service catalog automation.
