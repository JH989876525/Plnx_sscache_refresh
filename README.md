# USAGE
1. download sstate-cache.tar.gz from xilinx download center
2. put this script in to local mirror server  
    tree of local mirror server should be looks like
    ```
    LMirror2020.2.2
      ├── kv260
      │   └── downloads
      └── sstate-cache
          ├── refresh_sstate_cache.sh
          ├── sstate_aarch64_2020.2.2-k26
          └── sstate_aarch64_2020.2.2-k26.tar.gz
    ```
3. run this script
    ```
    ./refresh_sstate_cache.sh sure
    ```