# StandardInterfaces

<!-- TABLE OF CONTENTS -->
<details>
  <summary>Table of Contents</summary>
  <ol>
    <li>
      <a href="#about-the-project">About The Project</a>
      <ul>
        <li><a href="#built-with">Built With</a></li>
      </ul>
    </li>
    <li>
      <a href="#getting-started">Getting Started</a>
      <ul>
        <li><a href="#prerequisites">Prerequisites</a></li>
      </ul>
    </li>
    <li><a href="#license">License</a></li>
    <li><a href="#contact">Contact</a></li>
  </ol>
</details>



<!-- ABOUT THE PROJECT -->
## About The Project
Infosystem AG has a large variety of standard interface for its products. The interface description is publicly available for every party interested 
in connecting to one of Infosystems products:  
* performis
* leva+
* ressys

All interface are built with .net core/.net and use state of the art OpenAPI descriptions to enable third-party developer quickstart.<br>
All interfaces are built based on Infosystems Web API Standards, following the IETF RFCs regarding restful HTTP APIs.

<b>Interfaces</b><br>
At the moment, we enable third party developer to use the following modules via REST API:
- leva+
  - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/IF2leva.json&nocors" target="_blank"><b>Current</b> version documentation</a>
  - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2leva%20-%20Preview.json&nocors" target="_blank"><b>Preview</b> version documentation</a>
  
- performis - ERP
  - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/IF2performis.json&nocors" target="_blank"><b>Current</b> version documentation</a>
  - Preview
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2performis_finance_cost_accounting_entry.json&nocors" target="_blank"><b>Preview</b> Finance - Cost Accounting Entry</a>
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2performis_material_management_deliveryNote.json&nocors" target="_blank"><b>Preview</b> Material Management - Delivery Note</a>
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2performis_purchase_order.json&nocors" target="_blank"><b>Preview</b> Purchase - Order</a>
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2performis_purchase_supplier.json&nocors" target="_blank"><b>Preview</b> Purchase - Supplier</a>
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2performis_service_recording_absence.json&nocors" target="_blank"><b>Preview</b> Service Recording - Absence</a>
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2performis_service_recording_allowance.json&nocors" target="_blank"><b>Preview</b> Service Recording - Allowance</a>
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2performis_service_recording_allowance_definition.json&nocors" target="_blank"><b>Preview</b> Service Recording - Allowance Definitions</a>
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2performis_service_recording_service_provider.json&nocors" target="_blank"><b>Preview</b> Service Recording - Service Provider</a>
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2performis_service_recording_service_provider_day.json&nocors" target="_blank"><b>Preview</b> Service Recording - Service Provider Day</a>
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2performis_service_recording_service_record.json&nocors" target="_blank"><b>Preview</b> Service Recording - Service Record</a>
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2performis-finance-open-item-payment-status.json&nocors" target="_blank"><b>Preview</b> Finance - Payment Status</a>
  
- BAF - Business Application Functions
  - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/IF2BAF.json&nocors" target="_blank"><b>Current</b> version documentation</a>
  - Preview
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2BAF_fixed_assets.json.json&nocors" target="_blank"><b>Preview</b> Fixed Assets</a>
    - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Preview/IF2BAF_order.json&nocors" target="_blank"><b>Preview</b> Order</a>

- ressys
  - available soon


<b>Module-based interfaces</b><br>
Please use the product based services if available.
- performis FI - Financial Accounting
  - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Module-Based/IF2FI3.json&nocors" target="_blank">See documentation online</a>
- performis FA - Invoicing
  - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Module-Based/IF2FA3.json&nocors" target="_blank">See documentation online</a>
- performis BA - Base module
  - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Module-Based/IF2BA3.json&nocors" target="_blank">See documentation online</a>
- performis GP - Business Partner
  - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Module-Based/IF2GP3.json&nocors" target="_blank">See documentation online</a>
- leva+ - Master Data
  - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Module-Based/IF2BBA3.json&nocors" target="_blank">See documentation online</a>
- leva+ - Scheduling & Distribution
  - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Module-Based/IF2BHTR3.json&nocors" target="_blank">See documentation online</a>
- leva+ - Workshop
  - <a href="https://redocly.github.io/redoc/?url=https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Module-Based/IF2BWKST3.json&nocors" target="_blank">See documentation online</a>

All interfaces offer the same standard functionality to enable you to quickly learn and interact with them. If required, an API might offer enhanced functionality.

To see a graphical representation of the interface, please use the OpenAPI online editor https://editor.swagger.io or simply click the link below the API above.

<p align="right">(<a href="#top">back to top</a>)</p>

### Built With

All interfaces are built with:
* [.net](https://dotnet.microsoft.com/en-us/)
* [OpenAPI](https://swagger.io/specification/)

<p align="right">(<a href="#top">back to top</a>)</p>

<!-- GETTING STARTED -->
## Getting Started

Clone the github repository and load the OpenAPI files into your favorite API tester.
Speak with Infosystem about access to a test environment.

### Prerequisites

None

### Examples

Code value samples:
- leva+
  - <a href="https://raw.githubusercontent.com/InfosystemAGSwitzerland/StandardInterfaces/master/Examples/IF2LEVASampleCodes.md" target="_blank">Examples/IF2LEVASampleCodes.md</a>

<!-- LICENSE -->
## License
All rights reserved Infosystem AG.

<p align="right">(<a href="#top">back to top</a>)</p>


<!-- CONTACT -->
## Contact

Main Contact - [@Infosystem_AG](https://twitter.com/Infosystem_AG) - info@infosystem.ch<br>
Stefan Jud (Product Owner) - [@Stefan_Jud](https://www.linkedin.com/in/stefan-jud-4ba82b63/)

Project Link: [https://github.com/InfosystemAGSwitzerland/StandardInterfaces/](https://github.com/InfosystemAGSwitzerland/StandardInterfaces/)

<p align="right">(<a href="#top">back to top</a>)</p>
