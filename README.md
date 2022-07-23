# wx-treeList
微信小程序 树形菜单组件

需属性传值 listData（树形菜单数据）
listData数据格式:listData:[
            {
                title:'A层级菜单1',
                children:[
                    {
                        title:'B层级菜单1',
                        children:[],
                        isBind:true
                    },
                    {
                        title:'B层级菜单2',
                        children:[
                            {
                                title:'C层级菜单1',
                                children:[]
                            }
                        ]
                    }
                ]
            },
            {
                title:'A层级菜单2',
                children:[]
            }
        ]

使用：
<wxTreeList listData="{{listData}}"></wxTreeList>
