Given a set of candidate numbers (C) and a target number (T), find all unique combinations in C where the candidate numbers sums to T.

For example, given candidate set 2,3,6,7 and target 7, 
A solution set is: 
[7] 
[2, 2, 3] 

The same repeated number may be chosen from C unlimited number of times.

### ����
����һ�����ظ����飬��һ���������ܹ�����������������Կ���
�����ظ�ʹ�������е���

### ���
trick 1������������������ģ���Ҫ�Ÿ���
trick 2: Ҫ������Ĵ𰸱��밴���������

ֱ�������ͺã�����������def search(self, nums, sel, t, ans):
��ͣ�ļ��������ռ�ͺ�

tip: ��Ҫ��leetCode��ʹ��ȫ�ֱ�����ͬ�����㷨��ʹ��ȫ�ֱ����ᳬʱ�������ڱ��ر�������ʱ����һ�µġ�