def t_search (list, item):  #list：需要查询的列表，item：列表的标签
  first = 0
  last = len(list)-1
  while first <= last:
    half = (first + last)/2
    if list[half] == item:
      return half  #查询成功，返回标签值
    else:
      if list[half] > item:
        last = half-1
      else:
        first = half+1
  return None      #列表中没有这个元素
#------------使用方式-------------#

x=[2,3,4,5,6,7,8]

print t_search(x,5)    #起始标签为0
