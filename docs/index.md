# Welcome to MkDocs :smile: 

**bold** and _italic_ (r):fontawesome-regular-face-laugh-wink:

The `#!python range()` function is used to generate a sequence of numbers.

++ctrl+alt+del++

``` mermaid
stateDiagram-v2
  state fork_state <<fork>>
    [*] --> fork_state
    fork_state --> State2
    fork_state --> State3

    state join_state <<join>>
    State2 --> join_state
    State3 --> join_state
    join_state --> State4
    State4 --> [*]
```


- H~2~O
- A^T^A

- ==This was marked==
- ^^This was inserted^^
- ~~This was deleted~~


| Method      | Description                          |
| :---------- | :----------------------------------- |
| `GET`       | :material-check:     Fetch resource  |
| `PUT`       | :material-check-all: Update resource |
| `DELETE`    | :material-close:     Delete resource |


$$
\operatorname{ker} f=\{g\in G:f(g)=e_{H}\}{\mbox{.}}
$$


## 代码测试

``` js title="234"
/* 查找节点 */
search(num) {
    let cur = this.root;
    // 循环查找，越过叶节点后跳出
    while (cur !== null) {
        // 目标节点在 cur 的右子树中
        if (cur.val < num) cur = cur.right;
        // 目标节点在 cur 的左子树中
        else if (cur.val > num) cur = cur.left;
        // 找到目标节点，跳出循环
        else break;
    }
    // 返回目标节点
    return cur;
}

```

!!! note

    Lorem ipsum dolor sit amet, consectetur adipiscing elit. Nulla et euismod
    nulla. Curabitur feugiat, tortor non consequat finibus, justo purus auctor
    massa, nec semper lorem quam in massa.


=== "Python"

    ```python title=""
    class TreeNode:
        """二叉树节点类"""
        def __init__(self, val: int):
            self.val: int = val                   # 节点值
            self.left: Optional[TreeNode] = None  # 左子节点引用
            self.right: Optional[TreeNode] = None # 右子节点引用
    ```

=== "C++"

    ```cpp title=""
    /* 二叉树节点结构体 */
    struct TreeNode {
        int val;          // 节点值
        TreeNode *left;   // 左子节点指针
        TreeNode *right;  // 右子节点指针
        TreeNode(int x) : val(x), left(nullptr), right(nullptr) {}
    };
    ```