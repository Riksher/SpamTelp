#!bin/bash
clear
echo "****************************"

echo "____________________________"
echo "PEMBUAT DAFA/MR-D47 ID,KONTAK 089528100123"
echo "____________________________"
echo "****************************"
figlet Telp | lolcat
echo "::::::::::::::::::::::::::::::"
echo '
[1], telepon spam
[2], keluar &kontak admin
'
echo "::::::::::::::::::::::::::::::"
echo
read -p "masukan pilihan kalian lurd : " pil
if [[ $pil == 1 ]]; then
read -p "Masukan No Target contoh:89528100123  : " nomor
link="https://id.jagreward.com/member/verify-mobile/$nomor"
curl -s $link
else
echo "thanks ya lurd udah pakai tools MR-D47ID"
echo "kontak admin?089528100123"
exit
fi
echo
