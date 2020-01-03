 mkdir cli_tmp
 cd cli_tmp
 touch je_suis_dans_cli_tmp
 mkdir in_cli_tmp
 rm -rf je_suis_dans_cli_tmp
 rm -rf in_cli_tmp
 cd ..
 mkdir grand_parent parent grand_frere grande_soeur ami connaissances
 cd grand_frere
 touch bachir
 mv bachir ami
 cd ..
 cp -r ami parent
 rm -rf bob
 pwd
 cd ..
 rm -rf cli_tmp