# deds_oltp_erd_implementation

## Setup Instructions

### Prerequisites

Before setting up the database, make sure to execute the following commands on your PostgreSQL server.

#### Create User with Password

```sql
CREATE USER vincent WITH PASSWORD 'xxxx';
CREATE DATABASE MLM OWNER vincent;
```