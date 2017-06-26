

# ViewModelToModelMapping

Name|Value
---|---
Assembly|Catel.MVVM
Namespace|Catel.MVVM
Available on|.NET Framework 4.5, .NET Framework 4.6, Portable Class Libraries, Windows 10.0 (Universal Apps), Xamarin - Android, Xamarin - iOS

```
public class ViewModelToModelMapping
```

Model value class to store the mapping of the View Model to a Model mapping.



## Constructors

### ViewModelToModelMapping(string viewModelProperty, ViewModelToModelAttribute attribute)

Initializes a new instance of the [ViewModelToModelMapping](#) class.

#### Parameters

**viewModelProperty**
The view model property.

**attribute**
The [ViewModelToModelAttribute](#) that was used to define the mapping.

#### Exceptions

**T:System.ArgumentException**
The viewModelProperty is ```null``` or whitespace.



### ViewModelToModelMapping(string viewModelProperty, string modelProperty, string valueProperty, ViewModelToModelMode mode, Type converterType, object[] additionalConstructorArgs, string[] additionalPropertiesToWatch)

Initializes a new instance of the [ViewModelToModelMapping](#) class.

#### Parameters

**viewModelProperty**
The view model property.

**modelProperty**
The model property.

**valueProperty**
The value property.

**mode**
The mode.

**converterType**
Converter type

**additionalConstructorArgs**
Constructor args

**additionalPropertiesToWatch**

#### Exceptions

**T:System.ArgumentException**
The viewModelProperty is ```null``` or whitespace.



## Properties

### Converter

Gets the converter.
    


    The default value is TwoWay.



### ConverterType

Gets the type of the converter.
    


    The default value is TwoWay.



### Mode

Gets or sets the mode.



### ModelProperty

Gets the property name of the model.



### ValueProperties

Gets the property property name of the property in the model.



### ViewModelProperty

Gets the property name of the mapping of the view model.


