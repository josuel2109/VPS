# VPS#/bin/bash
clear
apt-get update && apt-get upgrade
clear
wget https://raw.githubusercontent.com/RicKbrL/VpsConf/master/conf && bash conf && wget https://raw.githubusercontent.com/RicKbrL/VpsPack/master/install && bash install
clear

echo -e "\033[1;37mConcluido"
	echo -e "\033[1;37mSeu servidor foi configurado"
	echo -e "\033[1;37mPara ver opções digite \033[1;31mVpsPack\033[1;37m_Edição por  \033[1;31muTrevor $0\033[0m"
