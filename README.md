# Salesforce-healthcare-case-automation
Salesforce Service Cloud project demonstrating healthcare member case automation using Apex, LWC, Flows, REST APIs, SOAP APIs, and MuleSoft integrations.
salesforce-healthcare-case-automation/
│
├── README.md
│
├── force-app/
│   └── main/
│       └── default/
│           ├── classes/
│           │   ├── MemberAPIService.cls
│           │   └── MemberAPIServiceTest.cls
│           │
│           ├── triggers/
│           │   └── CaseEscalationTrigger.trigger
│           │
│           ├── lwc/
│           │   └── memberCaseDashboard/
│           │       ├── memberCaseDashboard.html
│           │       ├── memberCaseDashboard.js
│           │       └── memberCaseDashboard.js-meta.xml
│           │
│           └── flows/
│               └── Case_Auto_Routing.flow-meta.xml
│
├── docs/
│   ├── architecture-diagram.png
│   └── integration-flow.png
│
└── package.xml
