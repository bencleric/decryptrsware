# decryptrsware
Decrypt RSware

1. Never delete any files that were encrypted
2. run sr sh
3. make sure to take the first file that were encrypted


bash decrypter/sr_files.sh  > sorted_list
head -1 sorted_list
$> ./d/home/user/.bash_logout.encrypted
python decrypter/decrypter.py -f ./d/home/user/.bash_logout.encrypted
$> [*] Seed: 1447255617
python decrypter/decrypter.py -s 1447255617 -l sorted_list -e error_list
