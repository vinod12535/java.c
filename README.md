# java.c
class stack:
    def __init__(self):
        self.items=[]
        
    def isEmpty(self):
     return self.items == []
    
    def push(self,item):
     self.items.append(item)
        
    def pop(self):
     return self.items.pop()
    
    def peek(self):
      return self.items[len(self.items)-1]
    
    def size(self):
      return len(self.items)
    
    def displsy(self):
      return(self.items)
s=stack()
print(s.isEmpty())
print(s.isEmpty())
print("push operations")
s.push(10)
s.push(11)
s.push(12)
s.push(14)
print("size:",s.size())

print("peek:",s.peek())
