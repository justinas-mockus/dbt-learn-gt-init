Welcome to your new dbt project!

### Using the starter project

Try running the following commands:
- dbt build


### Resources:
- Learn more about dbt [in the docs](https://docs.getdbt.com/docs/introduction)
- Check out [Discourse](https://discourse.getdbt.com/) for commonly asked questions and answers
- Join the [chat](http://slack.getdbt.com/) on Slack for live discussions and support
- Find [dbt events](https://events.getdbt.com) near you
- Check out [the blog](https://blog.getdbt.com/) for the latest news on dbt's development and best practices


### Using Codegen:
- dbtf run-operation generate_source --args '{"schema_name": "jaffle_shop", "database_name": "raw"}'
- dbtf run-operation generate_base_model --args '{"source_name": "jaffle_shop", "table_name": "customers"}'

### Recent work
- Built staging models for Jaffle Shop and Stripe sources, plus the `fct_orders` mart and Stripe payments model.
- Configured Stripe sources and updated model references; removed a deprecated customers model.
- Added data tests for customers and orders, and expanded model documentation, including order status descriptions.
- Set up the Codegen extension to help generate source and base-model definitions.
