#!/bin/bash
clear
echo -e "\e[4;31m Amine-crybto !!! \e[0m"
echo -e "\e[1;34m Presents \e[0m"
echo -e "\e[1;32m Smsbom \e[0m"
echo "Press Enter To Continue"
read a1
if [[ -s update.Amine-crybto ]];then
echo "All Requirements Found...."
else
echo 'Installing Requirements....'
echo .
echo .
apt install figlet toilet python curl -y
pip install urllib3 --user
pip install requests --user
echo This Script Was Made By Amine-crybto >update.Amine-crybto
echo Requirements Installed....
echo Press Enter To Continue...
read upd
fi
while :
do
clear
echo -e "\e[1;31m"
figlet Smsbom
echo -e "\e[1;34m Created By \e[1;32m"
toilet -f mono12 -F border Amine-crybto
echo -e "\e[4;34m This Project Was Created By Amine-crybto \e[0m"
echo -e "\e[1;34m For Any Queries Mail Me!!!\e[0m"
echo -e "\e[1;32m           Mail: amine333@list.ru \e[0m"
echo " "
echo -e "\e[4;31m Please Read Instruction Carefully !!! \e[0m"
echo " "
echo "Press S To  Start smsbom "
echo "Press U To  Update (Works On Linux And Linux Emulators) "
echo "Press E To  Exit "
read ch
if [ $ch -eq 1 ];then
clear
echo -e "\e[1;32m"
python3 prog.py
exit 0
elif [ $ch -eq 2 ];then
clear
echo -e "\e[1;32m"
python3 prog.py call
elif [ $ch -eq 3 ];then
clear
apt install git -y
echo -e "\e[1;34m Downloading Latest Files..."
git clone https://github.com/amine-crybto/smsbom
if [[ -s smsbom/smsbom.sh ]];then
cd smsbom
cp -r -f * .. > temp
cd ..
rm -rf  smsbom >> temp
rm update.amine-crybto >> temp
rm temp
chmod +x smsbom.sh
fi
echo -e "\e[1;32m TBomb Will Restart Now..."
echo -e "\e[1;32m All The Required Packages Will Be Installed..."
echo -e "\e[1;34m Press Enter To Proceed To Restart..."
read a6
./smsbom.sh
exit
elif [ $ch -eq 4 ];then
clear
echo -e "\e[1;32m"
python3 prog.py protect
elif [ $ch -eq 5 ];then
clear
echo -e "\e[1;33m"
figlet smsbom
echo -e "\e[1;34mCreated By \e[1;34m"
toilet -f mono12 -F border Amine-crybto
echo  " "
echo -e "\e[1;32m                   Features\e[1;34m"
echo "  [+] Unlimited And Super-Fast Attacking"
echo "  [+] International Attacking"
echo "  [+] Automated Future Updates"
echo -e "\e[1;32m                   Contributors\e[1;33m"
echo -e "\e[1;33m      [*]  Amine-crybto   \e[1;31m"
echo "         [-] Mail At: amine333@list.ru"
echo "         [-] Ping At: http://wa.me/917600140353"
echo -e "\e[1;33m      [*]  Rieltar   \e[1;31m"
echo "         [-] Ping At: https://t.me/Rieltar"
echo "         [-] Mail At: bennanimanagement@tutanota.com"
echo ""
echo ""
echo -e "\e[4;31m Good luck guys !!!\e[0m"
echo -e "\e[1;34m For Any Queries Mail Me!!!\e[0m"
echo -e "\e[1;32m           Mail: amine333@list.ru \e[0m"
echo "Press Enter To Go Home"
read a3
clear
elif [ $ch -eq 6 ];then
clear
echo -e "\e[1;31m"
figlet smsbom
echo -e "\e[1;34m Created By \e[1;32m"
toilet -f mono12 -F border Amine-crybto
echo -e "\e[1;34m For Any Queries Mail Me!!!\e[0m"
echo -e "\e[1;32m           Mail: amine333@list.ru \e[0m"
echo ""
exit 0
else
echo -e "\e[4;32m Invalid Input !!! \e[0m"
echo "Press Enter To Go Home"
read a3
clear
fi
done
