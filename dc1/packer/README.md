# add first iso
# then do below
E:\repo\packer-windows2016-standard> packer build -var 'iso_url=./iso/Windows_Server_2016_Datacenter_EVAL_en-us_14393_refresh.ISO' .\windows2016-standard.json

# the build box will be added to ..\build folder
# note if you have vbox or vmware workstation, it will run both, better remove vmware workstation
