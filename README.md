<<<<<<< HEAD
- reducer 里只能接受 state,不能改变 state  reducer 负责状态计算
- action 里存放不同状态对应的行动


- 全栈 react 项目
    1. api 不用写 用的第三方 sdk 后端
        http 跨域请求
        - 前后端的分离
            独立的前端路由可以用
            react-router-dom 
            符合职责分离模式
        
- 架构目录  
    src 开发目录 webpack context
    - api
        songs 不是内在数据 -> store -> reducer 函数
        -> dispatch action
    
    - bannerList[] -> 有数据 整个流程是怎么样的 
        - 先从后端 api 请求数据
        - getBannerList -> store/action -> dispatch(action){type:'',data:[]} -> reducer 重新计算

    
- immutable
    1.immutable数据就是一旦创建，就不能更改的数据。每当对Immutable对象进行修改的时候，就会返回一个新的Immutable对象，以此来保证数据的不可变
    
    2. API
        - fromJS() 完全地将一个 JS 对象或数组 转换为不可变地 Maps 或 Lists

        - is() 和 Object.is 类似的相等比较方法,比较两个Collection 是否有相同的值

        - hash()hash()方法是Immutable确认两个值是否相等和决定这些值如何存储的重要依据。传入任何数据，它将返回一个31位的整形

        - isImmutable() 返回True 表示这是一个不可变数据(Collection/Record)

        - isCollection() 返回True 表示这是一个集合(Collection) 或集合的子类

        - isKeyed() 返回 True 表示这是 Collection.key 或其子类

        - isIndexed() 返回True表示这是Collection.isIndexed或其子类

        - isAssociative() 返回True 表示这是 keyed 或者 Indexed Collection

        - isOrdered() 返回True表示这是一个Collection同时迭代索引设置正确。Collection.indexed、OrderedMap和OrderedSet会返回True
        
        - isValueObject() 返回True表示这是个JS对象并且同时拥有equals()和hashCode()方法。
=======
# cloud-music
>>>>>>> 2c78e046abf85360b847a6d1b7a1c7cbf3561f7f
