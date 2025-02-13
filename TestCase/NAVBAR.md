| | | | | | | | | | | |
|-|-|-|-|-|-|-|-|-|-|-|
|Project Name|Expanse Tracker (Frontend)| | | | | | | | | |
|Client|Abhishek| | | | | | | | | |
|Required Document |FRS ( Functional Requirement Specification| | | | | | | | | |
|Created By |Abhishek| | | | | | | | | |
|Creation Date |Feb 13, 2025| | | | | | | | | |
|Doc Type|private and public navbar test cases| | | | | | | | | |
| | | | | | | | | | | |
|Refernce Document |Test Scanrios ID|Test Scenarios|Test Case ID|Test Type|Test Case Description|Pre-requisite|Test Steps|Expected Results|Actual Results|HOW TO SOLVE BUG STEPS|
|Test Scenarios|TS_17|Verify Public Navbar|TC_PB_01|NA|Verify that the public navbar is visible before login|User is not logged in|Navigate to the homepage|The public navbar is displayed|PASS|NO BUG |
|Test Scenarios|TS_17|Verify Public Navbar|TC_PB_02|NA|Verify that the public navbar does not show private links|User is not logged in|Check the navbar menu|Only public links (e.g., Home, About, Login, Register) are visible|PASS|NO BUG |
|Test Scenarios|TS_17|Verify Public Navbar|TC_PB_03|NA|Verify that clicking on "Login" navigates to the login page|User is not logged in|Click on the "Login" button in the navbar|The login page is displayed|PASS|NO BUG |
|Test Scenarios|TS_17|Verify Public Navbar|TC_PB_04|NA|Verify that clicking on "Register" navigates to the Register page|User is not logged in|Click on the "Register" button in the navbar|The Register page is displayed|PASS|NO BUG |
|Test Scenarios|TS_17|Verify Public Navbar|TC_PB_05|NA|Verify that the public navbar is not visible after login|User is logged in|Navigate to the homepage after logging in|The public navbar should be hidden|PASS|NO BUG |
|Test Scenarios|TS_19|Verify Private Navbar	|TC_PVT_01|NA|Verify that the private navbar is visible after login|User is logged in|Navigate to any page|The private navbar is displayed|PASS|NO BUG |
|Test Scenarios|TS_19|Verify Private Navbar	|TC_PVT_02|NA|Verify that the private navbar contains user-specific options|User is logged in|Check the navbar menu|Private links like Dashboard, Profile, Logout are visible|PASS|NO BUG |
|Test Scenarios|TS_19|Verify Private Navbar	|TC_PVT_03|NA|Verify that clicking on "Dashboard" navigates to the dashboard page|User is logged in|Click on the "Dashboard" link in the navbar|The dashboard page is displayed|PASS|NO BUG |
|Test Scenarios|TS_19|Verify Private Navbar	|TC_PVT_04|NA|Verify that clicking on "Profile" navigates to the profile page|User is logged in|Click on the "Profile" link in the navbar|The profile page is displayed|PASS|NO BUG |
|Test Scenarios|TS_19|Verify Private Navbar	|TC_PVT_05|NA|Verify that clicking on "Logout" logs out the user and shows the public navbar|User is logged in|Click on the "Logout" button in the navbar|The user is logged out and the public navbar is displayed|PASS|NO BUG |
|Test Scenarios|TS_19|Verify Private Navbar	|TC_PVT_06|NA|Verify that the private navbar is not accessible after logout|User has logged out|Try accessing a private navbar link directly via URL|The user is redirected to the login page|PASS|NO BUG |
