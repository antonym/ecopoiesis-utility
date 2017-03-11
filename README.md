# ecopoiesis-utility

Used for discovery and population of craton db (WIP)

    ansible-playbook -i localhost discover.yml -e "craton_url=http://10.22.226.230:7780" \
                                               -e "craton_user=demo" \
                                               -e "craton_key=demo" \
                                               -e "craton_project"
