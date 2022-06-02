# tap-easybill

This is a [Singer](https://singer.io) tap that produces JSON-formatted data
following the [Singer
spec](https://github.com/singer-io/getting-started/blob/master/SPEC.md).

This tap:

- Pulls raw data from [Easybill API](https://www.easybill.de/api/#/)
- Extracts the following resources:
  - [Customers](https://www.easybill.de/api/#/customer/get_customers)
  - [Customer_Groups](https://www.easybill.de/api/#/customer%20group/get_customer_groups)
  - [Discounts_Position](https://www.easybill.de/api/#/discount/get_discounts_position)
  - [Documents](https://www.easybill.de/api/#/document/get_documents)
- Outputs the schema for each resource
- Incrementally pulls data based on the input state

---

Copyright &copy; 2021 SageData
