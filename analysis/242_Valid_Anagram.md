Given two strings s and t, write a function to determine if t is an anagram of s.

### ����
���������ַ������ж������Ƿ�Ϊanagram��

�����anagram��Ҫ����ĸ���ֵ�˳��һ����ֻҪ����ĸ���ֵĴ���һ���Ϳ����ˡ�

### ���
return sorted(s) == sorted(t)