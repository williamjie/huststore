## hexist ##

**Interface:** `/cache/hexist`

**Method:** `GET`

**Parameter:** 

*  **tb** (Required)  
*  **key** (Required)  

This interface is a proxy interface for `/hustcache/hexist`. See more details in [here](../../hustdb/hustcache/hexist.md).  

**Sample:**

    curl -i -X GET "http://localhost:8082/cache/hexist?tb=test_table&key=test_key"

[Previous](../cache.md)

[Home](../../../index.md)