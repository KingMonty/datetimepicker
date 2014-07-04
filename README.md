datetimepicker
==============
[Documentation][doc]


jQuery Plugin Date and Time Picker

DateTimePicker

This is a fork of the original https://github.com/xdan/datetimepicker by https://github.com/xdan

This fork adds support for specifying specific dates or date ranges to disable in the datepicker component.


To disable a specific date:

jQuery('#datetimepicker').datetimepicker({ disableDays: ['2014/07/13'] });

or 

jQuery('#datetimepicker').datetimepicker({ disableDays: ['2014/07/13','2014/07/16'] });

or 

jQuery('#datetimepicker').datetimepicker({ disableDays: ['Sunday'] });

or

jQuery('#datetimepicker').datetimepicker({ disableDays: ['Sunday','Wednesday'] });


To disable a date range:

jQuery('#datetimepicker').datetimepicker({ disableDateRange: ['2014/07/13','2014/07/22'] });


![ScreenShot](https://raw2.github.com/xdan/datetimepicker/master/screen/1.png)

DatePicker

![ScreenShot](https://raw2.github.com/xdan/datetimepicker/master/screen/2.png)

TimePicker

![ScreenShot](https://raw2.github.com/xdan/datetimepicker/master/screen/3.png)

[doc]: http://xdsoft.net/jqplugins/datetimepicker/
