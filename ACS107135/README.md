### 1.����s���ɮת��ظm�欰:<br>
------------------------------------
### �b /etc/hosts �ɮסA�Ч�X<br>
###  <li>���ɮת� inode ���X���X���H <br>
###  <li>�o�� inode �@���X���ɦW�b�ϥΡH<br>
<br>
�b" ls -al "���᭱�[�W�Ѽ�" i "�N�i�H�d���ɦW��inode���X�A�H�θ�inode�@���X���ɦW�b�ϥΡC<br>
![image](https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-5/ACS107135/photo/1.PNG)<br>

*****

### �إ߹���s���A��l�ɮ׬� /etc/hosts �ӷs���ɮ��ɦW�� /srv/hosts.hard�A�Ч�X<br>
###  <li>srv/hosts.hard�� inode ���X���X���H<br>
###  <li>�o�� inode �@���X���ɦW�b�ϥΡH<br>
###  <li>������]�C<br>
<br>
����: �Ϋ��O"ln"�ӫإ߹���s��(�o�̷|���o�{�@��ϥΪ̷|�����v�����������D�A�ҥH��������ϥΪ̤�����root�A�Ӷi��)�A�M���"ls -ali"�[���inode���X�M��s���ơC�N�|�o�{" /srv/hosts.hard�� inode ���X "�M" /etc/hosts �� inode ���X "�P�ˬҬ�" 4212682 "(��̬��P�@�ɮסA�u�O�ɦW���P)�A��inode���X���s���Ƥ]�q1���ܬ�" 2 "�C<br>
![image](https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-5/ACS107135/photo/2.PNG)<br>

*****

### �إ߲Ÿ��s���A��l�ɮ׬� /etc/hosts �ӷs���ɮ��ɦW�� /srv/hosts.soft�A�Ч�X<br>
###  <li>/srv/hosts.soft�� inode ���X���X���H<br>
###  <li>�o�� inode �@���X���ɦW�b�ϥ�<br>
###  <li>������]<br>
<br>
#### �� ln -s ���O�ӫإ߲Ÿ��s��(Symbolic Link)<br>
"-s"���إ߲Ÿ��s��(Symbolic Link)���ѼơC
<br>
�i�H�o��:<br>
1.inode ���X��" 12944883 "<br>
2.��inode�u��1���ɦW���b�ϥΡC<br>
<br>
����: Symbolic Link �P Hard Link ��̤��P�C<br>
" Hard Link "�O��@���ɮ׷s�W�X�@�Ӥ��P���ɦW�A���O�o2�Ӥ��P���ɦW�Ҷ}�Ҫ��O�P�@���ɮסA�ҥH�L�̪�inode�|�O�ۦP��(���P�@�ɮ�)�C<br>
" Symbolic Link "�O�إߤ@�ӷs�ɮװ����t�@���ɮ׶}�Ҫ����|�A2�̬����P���ɮסA�ҥH�۵Minode�N���|�ۦP(�����P�ɮ�)�C<br>
![image](https://github.com/ACS107135/107-1-ntcu-linux/blob/HW-5/ACS107135/photo/3.PNG)<br>
