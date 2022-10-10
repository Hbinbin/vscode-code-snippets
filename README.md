# 快速生成代码块

### vue3 的组件模板

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

### scss/sass 文件模板

```
$prefixCls: "";

.#{$prefixCls} {

}
```

#### useReactive

```
const [value, setValue] = useReactive(initialState.value)
```

#### useChildren

```
const children = useChildren(slots)
```

#### useMounted

```
const isMounted = useMounted()
```

### 文件引入

#### tool-components

```
import {} from '@lt/tool-components'
```

#### tool-base

```
import {} from '@lt/tool-base'
```

#### line-style

```
import {} from '@lt/line-style'
```

#### vue-hooks

```
import {} from '@lt/vue-hooks'
```
