# RemoveAllUpdates

## Remove multiple windows updates at once

extract 7z: PASS 1234

wmic qfe get | grep "Security Update" |sed "s/[\t ][\t ]*/ /g" |cut -d " " -f5 |cut -c 3- >remove.txt

