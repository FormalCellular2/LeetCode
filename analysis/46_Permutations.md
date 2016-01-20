Given a collection of distinct numbers, return all possible permutations.

### ����
����һ�����飬�������е�ȫ���п���

### ���
�ݹ��ȫ����Ӧ�ô�Ҷ����ˣ��Ͳ�˵��

�ǵݹ��д������

 def permute(self, nums):
    perms = [[]]   
    for n in nums:
        new_perms = []
        for perm in perms:
            for i in xrange(len(perm)+1):   
                new_perms.append(perm[:i] + [n] + perm[i:])   ###insert n
        perms = new_perms
    return perms