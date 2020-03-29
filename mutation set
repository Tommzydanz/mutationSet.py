
a1  = input()
a2 = set(map(int, raw_input().split()))
a3 = int(raw_input())

for i  in xrange(a3):
    p, q = raw_input().split()
    if p == "intersection_update":
			a2 &= set(map(int, raw_input().split()))
		elif p == "update":
			a2 |= set(map(int, raw_input().split()))
		elif p == "symmetric_difference_update":
			a2 ^= set(map(int, raw_input().split())) 
		else:
			p == "difference_update"
			a2 -= set(map(int, raw_input().split()))
			
print sum(list(a2))
