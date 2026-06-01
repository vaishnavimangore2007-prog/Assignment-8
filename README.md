# Assignment-8

a={1:"A",2:"B",3:"C",4:"D"}
print (a)

b = dict(sorted(a.items(), key=lambda item: item[1]))
print(b)

c = dict(sorted(a.items(), key=lambda item:item[1], reverse=True))
print(c)

a={1:"A",2:"B",3:"C",4:"D"}
print(1 in a)

d={5:"E",6:"F",7:"G"}
a.update(d)
print(a)

z=(1,2,3,4,5)
x=list(z)
print(type(x))
x.insert(5,6)
print(x)
z=tuple(x)
print(z)

q = (1,4.4,"abc,True")
print (q)

w = [1,2,3,4,5]
e = sum(w)
print(e)

w = [1,2,3,4,5]
print(max(w))

w = [1,2,3,4,5]
w.extend(["z","y"])
print(w)

w = [1,2,3,4,5]
w.reverse()
print(w)

w = [1,2,3,4,5]
print(w)
print(w[0])
print(w[3])