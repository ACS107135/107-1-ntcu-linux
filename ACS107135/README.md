### �Ш̻��������U�C�ާ@��������������������z�L�����ۤ����q�G<br>

#### ���bVirtalBox���إߤ@�ӷs��Host-only �����d�A���q��192.168.100.1/24<br>
![image](https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-8/ACS107135/photo/1.PNG)<br>
#### ���إߵ�������-1�A�ñҥ�host-only�����d�A�z�Lifconfig��ip���O�A�]�w��������-1��������192.168.100.100/24<br>
##### ��������-1:<br>
##### ip address add 198.168.100.100/24 broadcast + dev enp0s8 (�ݥ�������root)<br>
##### ip address show enp0s8 �d��
<center class="half">
    <img src="https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-8/ACS107135/photo/1.52.PNG"/><img src="https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-8/ACS107135/photo/2.PNG">
</center>

#### ���إߵ�������-2�A�ñҥ�host-only�����d�A�z�Lifconfig��ip���O�A�]�w��������-2��������192.168.100.200/24<br>
##### ��������-2:<br>
##### ip address add 198.168.100.200/24 broadcast + dev enp0s8 (�ݥ�������root)<br>
##### ip address show enp0s8 �d��<br>
<center class="half">
    <img src="https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-8/ACS107135/photo/1.5.PNG"><img src="https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-8/ACS107135/photo/3.PNG">
</center>

#### ���N�G�x���������������]�w�s��/etc/sysconfig/network-scripts/�U�۹�����ifcfg-*�ɮסA���s�Ұʵ��������A�T�{����ip�]�w�L�~�C<br>
##### vi /etc/sysconfig/network-scripts/ifcfg-enp0s8<br>
<center class="half">
    <img src="https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-8/ACS107135/photo/4.PNG"><img src="https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-8/ACS107135/photo/5.PNG">
</center><br>
��������-1(�W)/��������-2(�U)<br><br>
<center class="half">
    <img src="https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-8/ACS107135/photo/6.PNG"><img src="https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-8/ACS107135/photo/7.PNG">
</center>
#### ���q��������-1 ping ��������-2�T�{�����O�s�q�A�ñq��������-2 ping ��������-1�A�T�{�����]�O�s�q�C<br>
##### ping 198.168.100.xx �T�{�L�~<br>
��������-1(�W)/��������-2(�U)<br>
<center class="half">
    <img src="https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-8/ACS107135/photo/8.PNG"><img src="https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-8/ACS107135/photo/9.PNG">
</center>
