# AWS::QuickSight::Analysis DestinationParameterValueConfiguration<a name="aws-properties-quicksight-analysis-destinationparametervalueconfiguration"></a>

The configuration of destination parameter values\.

This is a union type structure\. For this structure to be valid, only one of the attributes can be defined\.

## Syntax<a name="aws-properties-quicksight-analysis-destinationparametervalueconfiguration-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-quicksight-analysis-destinationparametervalueconfiguration-syntax.json"></a>

```
{
  "[CustomValuesConfiguration](#cfn-quicksight-analysis-destinationparametervalueconfiguration-customvaluesconfiguration)" : CustomValuesConfiguration,
  "[SelectAllValueOptions](#cfn-quicksight-analysis-destinationparametervalueconfiguration-selectallvalueoptions)" : String,
  "[SourceField](#cfn-quicksight-analysis-destinationparametervalueconfiguration-sourcefield)" : String,
  "[SourceParameterName](#cfn-quicksight-analysis-destinationparametervalueconfiguration-sourceparametername)" : String
}
```

### YAML<a name="aws-properties-quicksight-analysis-destinationparametervalueconfiguration-syntax.yaml"></a>

```
  [CustomValuesConfiguration](#cfn-quicksight-analysis-destinationparametervalueconfiguration-customvaluesconfiguration): 
    CustomValuesConfiguration
  [SelectAllValueOptions](#cfn-quicksight-analysis-destinationparametervalueconfiguration-selectallvalueoptions): String
  [SourceField](#cfn-quicksight-analysis-destinationparametervalueconfiguration-sourcefield): String
  [SourceParameterName](#cfn-quicksight-analysis-destinationparametervalueconfiguration-sourceparametername): String
```

## Properties<a name="aws-properties-quicksight-analysis-destinationparametervalueconfiguration-properties"></a>

`CustomValuesConfiguration`  <a name="cfn-quicksight-analysis-destinationparametervalueconfiguration-customvaluesconfiguration"></a>
The configuration of custom values for destination parameter in `DestinationParameterValueConfiguration`\.  
*Required*: No  
*Type*: [CustomValuesConfiguration](aws-properties-quicksight-analysis-customvaluesconfiguration.md)  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`SelectAllValueOptions`  <a name="cfn-quicksight-analysis-destinationparametervalueconfiguration-selectallvalueoptions"></a>
The configuration that selects all options\.  
*Required*: No  
*Type*: String  
*Allowed values*: `ALL_VALUES`  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`SourceField`  <a name="cfn-quicksight-analysis-destinationparametervalueconfiguration-sourcefield"></a>
The source field ID of the destination parameter\.  
*Required*: No  
*Type*: String  
*Minimum*: `1`  
*Maximum*: `512`  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`SourceParameterName`  <a name="cfn-quicksight-analysis-destinationparametervalueconfiguration-sourceparametername"></a>
The source parameter name of the destination parameter\.  
*Required*: No  
*Type*: String  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)