# custom hooks

## useSafeState

> 实现要求：useSafeState，只有组件仍然存活的时候才进行 setState，参数和 useState 一样



## useUpdateEffect

> 实现要求：useUpdateEffect 一个只在依赖更新时执行的 useEffect hook，模拟 componentDidUpdate 生命周期，用法：
>
> ```tsx
> useUpdateEffect(
>   effect: () => (void | (() => void | undefined)),
>   deps?: deps,
> )
> ```



## useInfiniteScroll

> 实现要求：useInfiniteScroll 无限滚动 hook，参数自行定义



## useThrottle 和 useThrottleFn

> 实现要求：useThrottle 和 useThrottleFn 分别对值和函数进行节流