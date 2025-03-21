# AWS::WAFv2::WebACL VisibilityConfig<a name="aws-properties-wafv2-webacl-visibilityconfig"></a>

Defines and enables Amazon CloudWatch metrics and web request sample collection\. 

## Syntax<a name="aws-properties-wafv2-webacl-visibilityconfig-syntax"></a>

To declare this entity in your AWS CloudFormation template, use the following syntax:

### JSON<a name="aws-properties-wafv2-webacl-visibilityconfig-syntax.json"></a>

```
{
  "[CloudWatchMetricsEnabled](#cfn-wafv2-webacl-visibilityconfig-cloudwatchmetricsenabled)" : Boolean,
  "[MetricName](#cfn-wafv2-webacl-visibilityconfig-metricname)" : String,
  "[SampledRequestsEnabled](#cfn-wafv2-webacl-visibilityconfig-sampledrequestsenabled)" : Boolean
}
```

### YAML<a name="aws-properties-wafv2-webacl-visibilityconfig-syntax.yaml"></a>

```
  [CloudWatchMetricsEnabled](#cfn-wafv2-webacl-visibilityconfig-cloudwatchmetricsenabled): Boolean
  [MetricName](#cfn-wafv2-webacl-visibilityconfig-metricname): String
  [SampledRequestsEnabled](#cfn-wafv2-webacl-visibilityconfig-sampledrequestsenabled): Boolean
```

## Properties<a name="aws-properties-wafv2-webacl-visibilityconfig-properties"></a>

`CloudWatchMetricsEnabled`  <a name="cfn-wafv2-webacl-visibilityconfig-cloudwatchmetricsenabled"></a>
A boolean indicating whether the associated resource sends metrics to Amazon CloudWatch\. For the list of available metrics, see [AWS WAF Metrics](https://docs.aws.amazon.com/waf/latest/developerguide/monitoring-cloudwatch.html#waf-metrics) in the * AWS WAF Developer Guide*\.  
*Required*: Yes  
*Type*: Boolean  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`MetricName`  <a name="cfn-wafv2-webacl-visibilityconfig-metricname"></a>
A name of the Amazon CloudWatch metric dimension\. The name can contain only the characters: A\-Z, a\-z, 0\-9, \- \(hyphen\), and \_ \(underscore\)\. The name can be from one to 128 characters long\. It can't contain whitespace or metric names that are reserved for AWS WAF, for example `All` and `Default_Action`\.   
*Required*: Yes  
*Type*: String  
*Minimum*: `1`  
*Maximum*: `255`  
*Pattern*: `^[\w#:\.\-/]+$`  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)

`SampledRequestsEnabled`  <a name="cfn-wafv2-webacl-visibilityconfig-sampledrequestsenabled"></a>
A boolean indicating whether AWS WAF should store a sampling of the web requests that match the rules\. You can view the sampled requests through the AWS WAF console\.   
*Required*: Yes  
*Type*: Boolean  
*Update requires*: [No interruption](https://docs.aws.amazon.com/AWSCloudFormation/latest/UserGuide/using-cfn-updating-stacks-update-behaviors.html#update-no-interrupt)