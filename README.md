## **1. Overview**  
This project implements a **Record Manager** supporting table creation, record insertion, deletion, updates, and scans. It uses:  
- **Buffer Manager** for memory management  
- **Storage Manager** for file I/O  
- **Fixed-length schema** with records stored in page files  
## **2. Project Structure**  
The project is organized as follows:

assign3/ │── Makefile │── buffer_mgr.c / buffer_mgr.h │── dberror.c / dberror.h │── expr.c / expr.h │── record_mgr.c / record_mgr.h │── rm_serializer.c │── storage_mgr.c / storage_mgr.h │── tables.h │── test_assign3_1.c / test_expr.c / test_helper.h │── README.md

### **File Descriptions**  
| File(s)                 | Description |
|-------------------------|------------|
| `Makefile`              | Compilation script for building the project |
| `buffer_mgr.c / .h`     | Implements the Buffer Manager for page handling |
| `dberror.c / .h`        | Defines error messages and handling functions |
| `expr.c / .h`           | Implements expression evaluation for scans |
| `record_mgr.c / .h`     | Implements the Record Manager API |
| `rm_serializer.c`       | Provides serialization functions for records and schemas |
| `storage_mgr.c / .h`    | Implements file-based storage operations |
| `tables.h`              | Defines table structures and schemas |
| `test_assign3_1.c`      | Test cases for Record Manager functions |
| `test_expr.c`           | Test cases for expression evaluation |
| `test_helper.h`         | Helper functions for test cases |
| `README.md`             | Documentation for the project |
