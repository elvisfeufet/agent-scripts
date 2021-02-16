# agent-scripts
#!/bin/bash

if [ ${UID} -ne 0 ]
then
echo
echo "you need root access"
exit 1
fi
