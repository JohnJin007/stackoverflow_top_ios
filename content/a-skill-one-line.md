# 一行代码了事
___

1、当前选中的UITableView Index:

```objc
NSIndexPath *selectedIndexPath = [tableView indexPathForSelectedRow];
```

2、检测当前键盘是否弹出？

```
BOOL isFisrt =  [myTextField isFirstResponder]
```

3、移除字符串空格

```
NSString *stringWithoutSpaces = [myString stringByReplacingOccurrencesOfString:@" " withString:@""];
```

4、最顶层加一个View

```
[[[UIApplication sharedApplication] keyWindow] addSubview:someView]
```


