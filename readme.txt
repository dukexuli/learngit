�Ѵ���ŵ�������Ҫ3��
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