# Blue Medora ELK Stack Customizations

The base ELKstack has been modified in a few minor ways in order to capture web logs from vRealize Operations
Manager systems.  However, the changes are generic enough to be useful in several other cases.


* Filebeats listener on port 5044.  
* Multi-line parsing is enabled, looking for datetime string in order to disern a new line.
