# RemoveAllUpdates

'''
wmic qfe get | grep "Security Update" |sed "s/[\t ][\t ]*/ /g" |cut -d " " -f5 |cut -c 3- >remove.txt
'''
