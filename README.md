# Kotlin学习笔记
 * [基础](https://kotlinlang.org/)  
 * [高阶函数和lamda表达式]  
 * [关键字与操作符]  
 

关键字与操作符  
    硬关键字：以下符号会始终解释为关键字，不能用作标识符  
	-as  
		-用于类型转换  
		-为导入指定一个别名   
	-as?  
		-用于安全类型转换  
	-break
		-终止循环的执行
	-class
		-声明一个类
	-continue
		-继续最近层循环的下一步
	-do
		-开始一个do/while循环
	-else
	-false
	-for
	-fun
		-声明一个函数
	-if
	-in
		-指定for循环中迭代的对象
		-用作中缀操作符已检查一个值属于一个区间，一个集合或者其他定义contatins方法的实体
		-在when表达式中用于上述目的
		-将一个类型参数标记为逆变
	-!in
		-用作中缀操作符已检查一个值属于一个区间，一个集合或者其他定义contatins方法的实体
		-在when表达式中用于上述目的
	-interface
	-is
		-检查一个值具有指定类型
		-在when表达式中用于上述目的
	-!is
		-检查一个值不具有指定类型
		-在when表达式中用于上述目的
	-null
	-object
	-package
	-return
	-super
	-this
	-throw
	-true
	-try
	-typealias
		-声明一个类型别名
	-val
		-声明一个只读属性或局部变量
	-var
		-声明一个可变属性或局部变量
	-when
	-while
    软关键字：一下符号在使用的上下文中充当关键字，而在其他上下文中可用作标识符
	-by
	-catch
	-constructor
	-delegate
	-dynamic
	-field
	-file
	-finally
	-get
	-import
	-init
	-param
	-property
	-receiver
	-set
	-setparam
	-where
    修饰符关键字:以下符号作为声明中修饰符列表中的关键字，并可用作其他上下文中的标识符
	-actual
	-abstract
	-annotation
	-companion
	-const
	-crossinline
	-data
	-enum
	-expect
	-external
	-final
	-infix
	-inline
	-inner
	-internal
	-lateinit
	-noinline
	-open
	-operator
	-out
	-override
	-private
	-protected
	-public
	-reified
	-sealed
	-suspend
	-tailrec
	-vararg
    特殊标识符
        -field 用在属性访问器内部来引用该属性的幕后字段
	-it 用在lambda表达式内部来隐式引用其参数
    操作符和特殊符号

