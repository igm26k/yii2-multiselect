# igm26k/yii2-multiselect

Это форк [Flywi/yii2-multiselect](https://github.com/Flywi/yii2-multiselect) с внесенными исправлениями.
В этой версии корректно подгружаются значения из модели в правую часть.

![example](https://github.com/igm26k/yii2-multiselect/blob/master/example.png)

## Установка

```
$ php composer.phar require igm26k/yii2-multiselect
```

## Использование
`ActiveForm`:
```php
...
echo $form->field($model, 'attributeId')->widget(\igm26k\select\MultiSelectWidget::class, [
    'data' => [
      // select options list(key => value)
    ],
    'clientOptions' => [
    
    ],
]);
...
```
## Client options
clientOptions [crlcu/multiselect](https://github.com/crlcu/multiselect)
