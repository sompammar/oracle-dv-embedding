# Embed a Oracle Data Visualization dashboard in Oracle Jet application

## Introduction

In many cases you may need to embed Oracle Data Visualization (DV) dashboards in your custom application. To achieve this, you can start with starter template

Create a [Oracle Jet](https://docs.oracle.com/middleware/jet310/jet/developer/GUID-ACB7BD4E-BAAC-4A9E-B52A-6B2933CD222C.htm#JETDG-GUID-079D873B-5B18-4997-BD82-1B7E7095C382) web application using template of your choice. Or you can use the following sample

```script
cd ojet-sample
npm install
grunt serve
```

## Update Oracle DV Dashboard Details

Update the dashboard details in ```ojet-sample/src/js/viewModels/dashboard.js``` file. If you want to use the test dashboard, you can import it into your DV from following location ```dv-project/TestDashboard.dva```

More details about embedding visualizations at this [link](https://docs.oracle.com/en/cloud/paas/analytics-cloud/acubi/embedding-visualizations-web-pages-using-jet.html)
