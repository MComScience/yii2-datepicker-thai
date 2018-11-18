## Installation

To install

```
$ composer require m-comscience/yii2-datepicker-thai "@dev"
```

## Usage

```php
use mcomscience\datepicker\DatePicker;

// usage without model
echo \yii\helpers\Html::label('Date');
echo DatePicker::widget([
	'name' => 'date', 
	'value' => date('d/m/Y'), // 10/10/2561
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