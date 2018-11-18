## Installation

To install

```
$ composer require MComScience/yii2-widget-datepicker "*"
```

## Usage

```php
use mcomscience\datepicker\DatePicker;

// usage without model
echo \yii\helpers\Html::label('Date');
echo DatePicker::widget([
	'name' => 'date', 
	'value' => date('d/m/Y'),
	'options' => ['placeholder' => 'Select date ...'],
	'pluginOptions' => [
            'autoclose' => true,
            'format' => 'dd/mm/yyyy',
            'language' => 'th',
            'todayHighlight' => true,
            'todayBtn' => true,
        ],
]);
```