�Ѵ���ŵ�������Ҫ3��
git config --global user.name "duke"
git config --global user.email "466300686@qq.com"
һ �����汾��
����
1�� mkdir learngit  ��������Ϊlearngit���ļ��У����ڸ�Ŀ¼�£�
2�� cd learngit  �����Ŀ¼
3�� pwd  ��ʾ����Ŀ¼·��
4�� ls -ah ��ʾĿ¼�������ļ�

Git����
1�� git init ��ʼ��һ��Git�ֿ�
2����ӵ�Git �ֿ� ���� 
   1�� git add <file1> <file2> ���ļ���ӵ��ֿ�
   2�� git commit -m ��˵���� (-m���������˵��) �ύ���ֿ� 
   
�� ʱ�⴩��
 1) git status  �鿴git�汾�������µĶ�̬
 2��git diff ���鿴�޸�����
 3) ÿ���޸ĺ���Ҫ git add  ��git commit
 4) git log �鿴ÿ���޸ĵ�����
{�Ĳ��֣�1 commit id ���ύ�İ汾�ţ�2 author������ ����  3������ 4���ύ��ע}
5�� git log --pretty=oneline  ���Լ������� ֻ��ʾ 1��4�����������һ�У�  
6����git����head��ʾ��ǰ�汾��head^��һ���汾��head^^���ϸ��汾 ����head~100
   git reset --hard head^ ��һ���汾 cat readme.txt �鿴�������� 
7�� git reflog �鿴������ʷ���Ա�ȷ���ص�δ���Ǹ��汾

���������ݴ��� ��git���svn���Ǵ����ݴ����ĸ���
����ȥ��working directory�����������濴����Ŀ¼��
.git�������Ŀ¼��������㹤����������git�İ汾�⡣
�汾���ַ�Ϊ stage�ݴ��� ��git�ķ�֧master��headָ��ָ��ķ�֧��
1��git add ֻ�ǰ��ļ��޸���ӵ��ݴ���
2��gitcommit �ύ���ģ�ʵ���Ͼ��ǰ��ݴ��������������ύ����ǰ��֧��  

000000000000000000000000000000000000000

rm -f ./.git/index.lock ɾ���ļ�
clear ����

git �ֶ�add��commit �ᱻ�����ݴ������� git��������޸Ķ������ļ�
git diff head  --readme.txt

1�� git checkout --file  ֱ�Ӷ����������޸ĵ�����
2�� git reset head file ��������������
3�� �ύ��û������Զ�̿����ֱ�ӳ��ص���һ���汾��

