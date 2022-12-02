for file in *.pdf; do qpdf --decrypt --password=xxxxxx $file decrypted_$file; done
