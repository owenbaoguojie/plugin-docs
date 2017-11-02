# DatePickerRanges使用说明书

时间范围插件

## 目录

1. 使用目的
2. 使用方法
3. 案例介绍

## 1. 使用目的

![image](C:\Users\baoguojie\Desktop\datatimepicker\1.png)

![image](C:\Users\baoguojie\Desktop\datatimepicker\2.png)
![image](C:\Users\baoguojie\Desktop\datatimepicker\3.png) 

**********


``


$this->widget('ext.datetime-rangers-picker.DatePickerRanges', array(

    'id' => 'repurchase_date_range',
    'start_input' => 'start_date',
    'end_input' => 'end_date',
    'BsHtml_boolean' => true,
    'view_input_options' => [
        'id' => 'RepurchaseDateRange',
        'value' => '',
        'class' => 'repurchase_date_range',
        'label' => '日期:',
        'placeholder' => '日期范围',
        'styleOptions' => [
            'labelOptions' => ['class' => 'col-sm-4'],
            'controlOptions' => ['class' => 'col-sm-8'],
            'groupOptions' => ['class' => 'col-sm-4'],
        ]
    ],
    'hidden_input_options' => [

        'value' => [
            'start' => $start_date,
            'end' =>  $end_date
        ],
        'label' => [
            'start'=>'开始日期',
            'end' =>'结束日期'
        ],
    ],
));

``


