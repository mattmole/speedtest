# Speedtest
Simple script to time downloads and store timings within an RRD database.

The code can be called once and will run with a ten minute delay between readings, or called as a one-shot from Cron every ten minutes

## Run speed test

    cd /FOLDER
    python speedCheck.py
    
## To generate graphs

    cd /FOLDER
    python graph.py
    
## To configure

To configure, simply edit the `speedCheck.conf` file
