Given two strings s and t, determine if they are isomorphic.

Two strings are isomorphic if the characters in s can be replaced to get t.

All occurrences of a character must be replaced with another character while preserving the order of characters. No two characters may map to the same character but a character may map to itself.

### ��Ŀ
�ж������ַ����ǲ���ͬ�εġ�
ͬ��ָ�ĵ����ǵ���ĸ���и�ӳ���ϵ������ʸ��ַ����е��ַ��������ӳ���ϵȫ����������ô���ܵõ�����һ���ַ�����
�����ַ�����ӳ�䵽ͬһ���ַ���
��Ŀ��֤�������ַ���������ͬ��

### ���
�����map���͵�Ӧ�á�
map[s[i]] = j[i]�Ϳ��Լ�¼���ֹ�ϵ��
�ڿ�ʼǰ�ж�һ�����߳��ֵ��ַ������Ƿ���ͬ������ȥ�ж� map[j[i]] = s[i]��