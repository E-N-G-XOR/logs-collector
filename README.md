# logs-collector

The script needs to be downloaded and run directly on the host using the `root` user or using `sudo`.

## How to use

* Download the script and save as: `rancher_logs_collector.sh`
* Make sure the script is executable: `chmod +x rancher_logs_collector.sh`
* Run the script: `./rancher_logs_collector.sh`

### To change the default output directory, please use one of the following.
* `DIR="/mnt/data/logs/" ./rancher_logs_collector.sh`
* `./rancher_logs_collector.sh --dir "/mnt/data/logs/"`
