for file in *.pdf; do qpdf --decrypt --password=22051997 $file decrypted_$file; done
