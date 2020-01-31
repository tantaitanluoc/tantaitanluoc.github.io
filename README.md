# Tiêu điểm code:

### *Làm thế nào để tìm max của hai số mà không dùng đến cấu trúc rẽ nhánh?*
### *How do I find out the maximum of two number without branching?*

```js 
function max(x,y){
	return x ^ ((x ^ y) & -(x < y));
}
```
> Chứng minh:   
> - Nếu x < y:   
>		-(x < y) = true (tất cả bit 1)  
>		Suy ra:   
>		x ^ ((x ^ y) & true) = x ^ x ^ y   
>							 = y   
> - Nếu x >= y:  
>		-(x < )y = false (tất cả bit 0)  
>		Suy ra:  
>		x ^ ((x ^ y) & false) = x ^ 0   
>							  = x  




Contact me:
  [Facebook](https://fb.com/d3t.tantai)
  [Twitter](https://twitter.com/tantaitanluoc)
