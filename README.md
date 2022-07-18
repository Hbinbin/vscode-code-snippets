# 快速生成代码块

vue3的组件模板
```
import { watchEffect } from 'vue'
import { useDefineComponent, useReactive } from '@lt/vue-hooks';
import './index.scss';

// interface
interface IProps {
}

const Name = useDefineComponent<IProps>({
    props: [],
    setup(props, { attrs }) {
        return () => {
            return <div class=''></div>;
        }
    }
})

export default Name
```

sass文件模板
```
$prefixCls: "";

.#{$prefixCls} {

}
```

useReactive

```
const [value, setValue] = useReactive(initialState.value)
```

useChildren
```
const children = useChildren(slots)
```

useMounted
```
const isMounted = useMounted()
```