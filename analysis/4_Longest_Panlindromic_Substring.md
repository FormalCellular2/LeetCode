Given a string S, find the longest palindromic substring in S. You may assume that the maximum length of S is 1000, and there exists one unique longest palindromic substring.

### ����
����һ���ַ���������Ļ����ִ�

### ���
ʹ��Manacher's Algorithm������O(n)��ʱ������⣬�൱���ʡ�
 > http://www.felix021.com/blog/read.php?2040
�㷨�Ļ���˼���Ǽ�¼�˰�����ǰ����������ִ�λ�ӣ����ڶԳ��ԣ���ǰ���Ļ��ĳ��ȣ����ٵ��ں����ԳƵ��Ǹ��ڵ�Ļ��ĳ��ȡ�

ͨ�����ַ��� abc ��Ϊ #a#b#c# ��������ʽ��ֻ�ÿ����������ģ������ÿ���ż������
 
��׺����Ҳ��������