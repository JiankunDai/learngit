Git is a distributed version control system.
Git is free software distributed under the GPL.
Git has a mutable index called stage.
Git tracks changes of files.


Ŀǰ����GitHub�ϵ����learngit�ֿ⻹�ǿյģ�GitHub�������ǣ����Դ�����ֿ��¡���µĲֿ⣬Ҳ���԰�һ�����еı��زֿ���֮������Ȼ�󣬰ѱ��زֿ���������͵�GitHub�ֿ⡣

���ڣ����Ǹ���GitHub����ʾ���ڱ��ص�learngit�ֿ����������

$ git remote add origin git@github.com:michaelliao/learngit.git
��ǧ��ע�⣬�������michaelliao�滻�����Լ���GitHub�˻������������ڱ��ع����ľ����ҵ�Զ�̿⣬����û�����⣬�������Ժ��������Ʋ���ȥ�ģ���Ϊ���SSH Key��Կ�����ҵ��˻��б��С�

��Ӻ�Զ�̿�����־���origin������GitĬ�ϵĽз���Ҳ���Ըĳɱ�ģ�����origin�������һ����֪����Զ�̿⡣

��һ�����Ϳ��԰ѱ��ؿ�������������͵�Զ�̿��ϣ�

$ git push -u origin master
Counting objects: 20, done.
Delta compression using up to 4 threads.
Compressing objects: 100% (15/15), done.
Writing objects: 100% (20/20), 1.64 KiB | 560.00 KiB/s, done.
Total 20 (delta 5), reused 0 (delta 0)
remote: Resolving deltas: 100% (5/5), done.
To github.com:michaelliao/learngit.git
 * [new branch]      master -> master
Branch 'master' set up to track remote branch 'master' from 'origin'.
�ѱ��ؿ���������͵�Զ�̣���git push���ʵ�����ǰѵ�ǰ��֧master���͵�Զ�̡�

����Զ�̿��ǿյģ����ǵ�һ������master��֧ʱ��������-u������Git������ѱ��ص�master��֧�������͵�Զ���µ�master��֧������ѱ��ص�master��֧��Զ�̵�master��֧�������������Ժ�����ͻ�����ȡʱ�Ϳ��Լ����