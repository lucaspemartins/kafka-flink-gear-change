### Script content to run flink gear change

_run-flink-gearchange.sh_

    #!/bin/bash 
    
    cd kafka-flink-gear-change
    
    mvn exec:java -Dexec.mainClass=com.inatel.demos.GearChange

