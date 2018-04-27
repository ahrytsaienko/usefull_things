### Clear terminal
#### ctrl-k
---

### Kill sesssions
#### sudo pkill postgres

### Select all enums in type
#### select enum_range(null::supplier_sku_status_type);


### delete enum in type
#### DELETE FROM pg_enum en WHERE en.enumtypid=124 AND en.enumlabel='unique';

