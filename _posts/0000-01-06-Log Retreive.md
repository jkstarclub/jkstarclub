az webapp log download --log-file \<_filename_\>.zip  --resource-group \<_resource group name_\> --name \<_app name_\>
az webapp log download --log-file contosofashions.zip  --resource-group learn-d4267545-172c-4693-a299-2864b8033186 --name contosofashions23868
<br />
zipinfo -1 contosofashions.zip
unzip -j contosofashions.zip LogFiles/Application/3c2c82-5884-637530798555333248.txt
code 3c2c82-5884-637530798555333248.txt
