Makefile_templet -- Makefile templet for Linux
=======================

PROJECT
=======================
files for Makefile
* Makefile��the default Makefile, for all files in ONE directory(c or c++), auto detect the target(.so or .a or binary file)
* one_dir_project��Makefile demo
* mult_dir_project��Makefile for multi directory(ref u-boot)
* mult_dir_project_new��a new version for multi directory(not u-boot)
* linux_driver��Makefile for linux driver demo

USAGE
=======================
* Just put Makefile under the project directory, and just make it.
* For more, you may want to modify head files directory, source files directory, compiler flags and the target file name.
* What to modify? see "!!!=== " in the Makefile. If you want to delete the .a or .so files, specify the name under clean.
* By default, type��make
* For more compile information, type:make V=1  (V is uppercase)
* For debug version, type: make debug=y
* For release version, type: make debug=n
* For cross compile, type��make CROSS_COMPILE=arm-linux-
* For multi directory, type��make SRC_DIR1=foo SRC_DIR2=bar SRC_DIR3=crc

NOTES
=======================
For the Linux kernel, you need to specify the .o files under Makefile.

COPYRIGHT
=======================
Copyright by Late Lee, but anyone can use it for any purporse(study or bussiness), any problems, pls let me know.

AUTHOR
=======================
Late Lee (li@latelee.org) <br>

[CST studio](http://www.latelee.org) welcome donate!

last update: <br>
2018.1.27 <br>


Makefile_templet -- Linux������Makefileģ��
=======================

����˵��
=======================
���ֿ����Makefileʾ����
* Makefile��Ĭ�ϵ�Makefile�����Ŀ¼�������ļ�(c/c++)������Ŀ���ļ������ǿ��ļ����ǿ�ִ���ļ���
* one_dir_project����Ŀ¼����ʾ��
* mult_dir_project����Ŀ¼����ʾ��(�ο�uboot��)
* mult_dir_project_new���ɵ�Ŀ¼���̵�Makefile������ɣ�������uboot�汾
* linux_driver��linux������Makefileģ�弰�����ʾ����

�÷�
=======================
* Ĭ������£�ֱ���ڽ���Makefile�ŵ���һ�Ĺ���Ŀ¼��make���ɡ�
* ���ݹ���ʵ��������޸�ͷ�ļ�����Ŀ¼��Դ��Ŀ¼������ѡ��(����Ӷ�̬/��̬��)���Լ������ļ�����
* Ҫ�޸ĵĵط��Ѿ�ʹ�� !!!=== ����ʾ�����⣬���Ҫɾ�����ɵ�.a��.so����Ҫ��clean�����ɾ�����ļ�(��ģ�岻��.a��ƥ��)��
* Ĭ�ϱ��룺make
* ��ϸ���������Ϣ��make V=1  (VΪ��д)
* ���԰汾��make debug=y
* �ǵ��԰汾��make debug=n
* �������汾��make CROSS_COMPILE=arm-linux-
* ��Ŀ¼�汾��make SRC_DIR1=foo SRC_DIR2=bar SRC_DIR3=crc

ע������
=======================
�ں�Makefile��Ҫ�ֶ�ָ������������ļ�(.o��ʽ)��ʹ��ͨ���ƥ���޷����롣

��Ȩ
=======================
��Ȩ���С�<br>
��Ŀ¼�����ļ����������κ�Ŀ�ġ�����(����ѧϰ�о�������)����ӭ���ʹ�ã��κ�����ɷ��������ߡ�

����
=======================
˼�ù����� ���(Late Lee at li@latelee.org) <br>

[��˼�ù�����](http://www.latelee.org) ��ӭ�������ߣ�

last update: <br>
2018.1.27 <br>
