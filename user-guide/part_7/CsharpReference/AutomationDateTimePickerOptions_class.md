# AutomationDateTimePickerOptions class

Below, you find an overview of all members of the *AutomationDateTimeUpDownOptions* class.

- [AutomationDateTimePickerOptions methods](AutomationDateTimePickerOptions_methods.md)

- [AutomationDateTimePickerOptions properties](AutomationDateTimePickerOptions_properties.md)

This C# class allows you to create a date and time picker control in an interactive Automation script.

For example:

```txt
UIBlockDefinition blockDateTimePickerDefault = new UIBlockDefinition();
blockDateTimePickerDefault.Type = UIBlockType.Time;
AutomationDateTimePickerOptions configOptionsDateTimePickerDefault = new AutomationDateTimePickerOptions();
blockDateTimePickerDefault.ConfigOptions = configOptionsDateTimePickerDefault;
```

![](../../images/datetimepicker_example.png)



> [!NOTE]
> If the name of a variable starts with the following prefix, IntelliSense will list the object properties: *dateTimePickerConfig\**
>