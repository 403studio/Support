# Support

为PHP的日常开发提供小巧便捷的小工具

## Usage

### Collection

```
use Support\Collection;

$arr = array('id' => 1, 'name' => 'hao.huang');
$collection = new Collection($arr);
echo $collection['id'];
echo $collection->id;
echo $collection->get('id');
```

## Change Log