# **Autonomous tractor path deployment and package mangment of version -- 1.0**  
Here package need to be:
>  Reusability  
>  Standardization  
>  Efficiency  
>  Flexibility  

## **Reusability** 
Package is design by using c, python language and bson file system , here code reusability is achieved primarily through functions, header files, and libraries which are  
>  **POSIX - UART**  
>  **POSIX - I2C**  
>  **POSIX - SPI**  
>  **NMEA Parser**    
- RMC  
- GGA
- VTG
- GLL  
- GSA    
>  **Motion planning**  
- Mathematical modelling
- Path Read  
- Serial write  
- logger
>  **Path planning**
- Admin Interface
- Tractor User Interface 
- Path generation
- Path validation
- Main
> **Database**
- Read GCP
- Read Path check points
- Read Admin command
- Write gnss
- Write Motion path
- Write streaming
- Write planned path design
## **Standardization**
>  **Mongodb ATLAS**  
>  **C gcc**  
>  **python**  
>  **leaflet js**  
>  **BSON**  
>  **shell**  
>  **Service files**
## **Efficiency**  
C provides direct control over memory management through pointers, allowing programmers to optimize memory usage and access hardware resources directly.  
This package design in microprocessor by using 512mb RAM. 


