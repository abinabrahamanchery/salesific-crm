# Developer Guide

You need to sign the [contributor license agreement](cla.md) before you contribute to Salesific CRM. Salesific CRM is 
licensed under GNU/GPLv3 license. Please refer to the file contributing.md on the root directory.

# Internationalization

Internationalization is handled by the module `Salesific.i18n`. For more information, read the [internationalization guide](i18n.md).

# Data Access & Restful APIs

Salesific CRM uses database first approach. Please follow these documents for more information:

- [Database of Salesific CRM](db.md)
- [Creating Data Transfer Objects](dto.md)
- [Creating Data Access Repositories](data-access/repository.md)
- [Creating Data Access Classes](data-access/dac.md)
- [Creating Restful Web API](rest/api.md)
- [Writing Tests against Web APIs](rest/test.md)

# Frontend Development

For the frontend development tasks, Salesific CRM uses:

- jQuery
- AngularJS
- Semantic UI
- MixERP ScrudFactory framework for CRUD operations.
- d3 and chartjs for Charting
- linq.js for client side LINQ
- papaparse for CSV parsing
- qunit for writing tests.