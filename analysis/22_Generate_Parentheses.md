Given n pairs of parentheses, write a function to generate all combinations of well-formed parentheses.

For example, given n = 3, a solution set is:

"((()))", "(()())", "(())()", "()(())", "()()()"

### ����
��������n����������n�����ŵĺϷ����

### ���
���ǵ���i�������ţ���������ֱ�ӷ��ڵ�ǰλ��j
���λ��j���Է���m���Ϸ��������ţ�����ô��i�������ſ��Է�����m���������е�����һ������
���Ե�i�������ţ��� 1 + m ��λ�ÿ��Է�

��������˵�k�������ŵĺ��棬��ô��һ��������ֻ�� m - k + 1 ���Ϸ��ķ���λ��

�ݹ������� 