#### [DevUniverse.Pipelines.Core](Pipelines.md 'Pipelines')
### [DevUniverse.Pipelines.Core.Builders](Pipelines.md#DevUniverse.Pipelines.Core.Builders 'DevUniverse.Pipelines.Core.Builders')
## IPipelineBuilderAsync&lt;TParam0,TResult&gt; Interface
The pipeline builder with 1 parameter which returns the result asynchronously.  
```csharp
public interface IPipelineBuilderAsync<TParam0,TResult> :
DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync,
DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderBasic,
DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilder<System.Func<TParam0, TResult>, DevUniverse.Pipelines.Core.Steps.IPipelineStep<TParam0, TResult>, System.Func<TParam0, System.Threading.Tasks.Task<bool>>, DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync<TParam0>, DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync<TParam0, TResult>>,
DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterface<System.Func<TParam0, TResult>, DevUniverse.Pipelines.Core.Steps.IPipelineStep<TParam0, TResult>, DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync<TParam0, TResult>>,
DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderCore<System.Func<TParam0, TResult>, DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync<TParam0, TResult>>,
DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterfaceWithServiceProvider<System.Func<TParam0, TResult>, DevUniverse.Pipelines.Core.Steps.IPipelineStep<TParam0, TResult>, DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync<TParam0, TResult>>,
DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderWithServiceProvider<System.Func<TParam0, TResult>, DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync<TParam0, TResult>>,
DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegate<System.Func<TParam0, TResult>, System.Func<TParam0, System.Threading.Tasks.Task<bool>>, DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync<TParam0, TResult>>,
DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterface<System.Func<TParam0, TResult>, DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync<TParam0>, DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync<TParam0, TResult>>,
DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegateWithServiceProvider<System.Func<TParam0, TResult>, System.Func<TParam0, System.Threading.Tasks.Task<bool>>, DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync<TParam0, TResult>>,
DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterfaceWithServiceProvider<System.Func<TParam0, TResult>, DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync<TParam0>, DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync<TParam0, TResult>>
    where TResult : System.Threading.Tasks.Task
```
#### Type parameters
<a name='DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0'></a>
`TParam0`  
The type of the 1st parameter.
  
<a name='DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult'></a>
`TResult`  
The type of the result.
  

Implements [IPipelineBuilderAsync](IPipelineBuilderAsync.md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync'), [IPipelineBuilderBasic](IPipelineBuilderBasic.md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderBasic'), [DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilder&lt;](IPipelineBuilder.TDelegate.TPipelineStep.TPredicate.TPipelineCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilder&lt;TDelegate,TPipelineStep,TPredicate,TPipelineCondition,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilder.TDelegate.TPipelineStep.TPredicate.TPipelineCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilder&lt;TDelegate,TPipelineStep,TPredicate,TPipelineCondition,TResult&gt;')[DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;](IPipelineStep.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineStep.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineStep.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;TParam0,TResult&gt;')[,](IPipelineBuilder.TDelegate.TPipelineStep.TPredicate.TPipelineCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilder&lt;TDelegate,TPipelineStep,TPredicate,TPipelineCondition,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[System.Threading.Tasks.Task&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task-1 'System.Threading.Tasks.Task`1')[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task-1 'System.Threading.Tasks.Task`1')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilder.TDelegate.TPipelineStep.TPredicate.TPipelineCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilder&lt;TDelegate,TPipelineStep,TPredicate,TPipelineCondition,TResult&gt;')[DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync&lt;](IPipelineConditionAsync.TParam0..md 'DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync&lt;TParam0&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[&gt;](IPipelineConditionAsync.TParam0..md 'DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync&lt;TParam0&gt;')[,](IPipelineBuilder.TDelegate.TPipelineStep.TPredicate.TPipelineCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilder&lt;TDelegate,TPipelineStep,TPredicate,TPipelineCondition,TResult&gt;')[DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[&gt;](IPipelineBuilder.TDelegate.TPipelineStep.TPredicate.TPipelineCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilder&lt;TDelegate,TPipelineStep,TPredicate,TPipelineCondition,TResult&gt;'), [DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterface&lt;](IPipelineBuilderStepInterface.TDelegate.TPipelineStep.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterface&lt;TDelegate,TPipelineStep,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilderStepInterface.TDelegate.TPipelineStep.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterface&lt;TDelegate,TPipelineStep,TResult&gt;')[DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;](IPipelineStep.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineStep.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineStep.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;TParam0,TResult&gt;')[,](IPipelineBuilderStepInterface.TDelegate.TPipelineStep.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterface&lt;TDelegate,TPipelineStep,TResult&gt;')[DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[&gt;](IPipelineBuilderStepInterface.TDelegate.TPipelineStep.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterface&lt;TDelegate,TPipelineStep,TResult&gt;'), [DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderCore&lt;](IPipelineBuilderCore.TDelegate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderCore&lt;TDelegate,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilderCore.TDelegate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderCore&lt;TDelegate,TResult&gt;')[DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[&gt;](IPipelineBuilderCore.TDelegate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderCore&lt;TDelegate,TResult&gt;'), [DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterfaceWithServiceProvider&lt;](IPipelineBuilderStepInterfaceWithServiceProvider.TDelegate.TPipelineStep.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterfaceWithServiceProvider&lt;TDelegate,TPipelineStep,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilderStepInterfaceWithServiceProvider.TDelegate.TPipelineStep.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterfaceWithServiceProvider&lt;TDelegate,TPipelineStep,TResult&gt;')[DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;](IPipelineStep.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineStep.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineStep.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Steps.IPipelineStep&lt;TParam0,TResult&gt;')[,](IPipelineBuilderStepInterfaceWithServiceProvider.TDelegate.TPipelineStep.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterfaceWithServiceProvider&lt;TDelegate,TPipelineStep,TResult&gt;')[DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[&gt;](IPipelineBuilderStepInterfaceWithServiceProvider.TDelegate.TPipelineStep.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.StepInterface.IPipelineBuilderStepInterfaceWithServiceProvider&lt;TDelegate,TPipelineStep,TResult&gt;'), [DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderWithServiceProvider&lt;](IPipelineBuilderWithServiceProvider.TDelegate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderWithServiceProvider&lt;TDelegate,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilderWithServiceProvider.TDelegate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderWithServiceProvider&lt;TDelegate,TResult&gt;')[DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[&gt;](IPipelineBuilderWithServiceProvider.TDelegate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.IPipelineBuilderWithServiceProvider&lt;TDelegate,TResult&gt;'), [DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegate&lt;](IPipelineBuilderConditionDelegate.TDelegate.TPredicate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegate&lt;TDelegate,TPredicate,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilderConditionDelegate.TDelegate.TPredicate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegate&lt;TDelegate,TPredicate,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[System.Threading.Tasks.Task&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task-1 'System.Threading.Tasks.Task`1')[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task-1 'System.Threading.Tasks.Task`1')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilderConditionDelegate.TDelegate.TPredicate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegate&lt;TDelegate,TPredicate,TResult&gt;')[DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[&gt;](IPipelineBuilderConditionDelegate.TDelegate.TPredicate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegate&lt;TDelegate,TPredicate,TResult&gt;'), [DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterface&lt;](IPipelineBuilderConditionInterface.TDelegate.TCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterface&lt;TDelegate,TCondition,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilderConditionInterface.TDelegate.TCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterface&lt;TDelegate,TCondition,TResult&gt;')[DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync&lt;](IPipelineConditionAsync.TParam0..md 'DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync&lt;TParam0&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[&gt;](IPipelineConditionAsync.TParam0..md 'DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync&lt;TParam0&gt;')[,](IPipelineBuilderConditionInterface.TDelegate.TCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterface&lt;TDelegate,TCondition,TResult&gt;')[DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[&gt;](IPipelineBuilderConditionInterface.TDelegate.TCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterface&lt;TDelegate,TCondition,TResult&gt;'), [DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegateWithServiceProvider&lt;](IPipelineBuilderConditionDelegateWithServiceProvider.TDelegate.TPredicate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegateWithServiceProvider&lt;TDelegate,TPredicate,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilderConditionDelegateWithServiceProvider.TDelegate.TPredicate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegateWithServiceProvider&lt;TDelegate,TPredicate,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[System.Threading.Tasks.Task&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task-1 'System.Threading.Tasks.Task`1')[System.Boolean](https://docs.microsoft.com/en-us/dotnet/api/System.Boolean 'System.Boolean')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Threading.Tasks.Task-1 'System.Threading.Tasks.Task`1')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilderConditionDelegateWithServiceProvider.TDelegate.TPredicate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegateWithServiceProvider&lt;TDelegate,TPredicate,TResult&gt;')[DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[&gt;](IPipelineBuilderConditionDelegateWithServiceProvider.TDelegate.TPredicate.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionDelegate.IPipelineBuilderConditionDelegateWithServiceProvider&lt;TDelegate,TPredicate,TResult&gt;'), [DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterfaceWithServiceProvider&lt;](IPipelineBuilderConditionInterfaceWithServiceProvider.TDelegate.TCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterfaceWithServiceProvider&lt;TDelegate,TCondition,TResult&gt;')[System.Func&lt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](https://docs.microsoft.com/en-us/dotnet/api/System.Func-2 'System.Func`2')[,](IPipelineBuilderConditionInterfaceWithServiceProvider.TDelegate.TCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterfaceWithServiceProvider&lt;TDelegate,TCondition,TResult&gt;')[DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync&lt;](IPipelineConditionAsync.TParam0..md 'DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync&lt;TParam0&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[&gt;](IPipelineConditionAsync.TParam0..md 'DevUniverse.Pipelines.Core.Conditions.IPipelineConditionAsync&lt;TParam0&gt;')[,](IPipelineBuilderConditionInterfaceWithServiceProvider.TDelegate.TCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterfaceWithServiceProvider&lt;TDelegate,TCondition,TResult&gt;')[DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TParam0](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TParam0 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TParam0')[,](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[TResult](IPipelineBuilderAsync.TParam0.TResult..md#DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync.TParam0.TResult..TResult 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;.TResult')[&gt;](IPipelineBuilderAsync.TParam0.TResult..md 'DevUniverse.Pipelines.Core.Builders.IPipelineBuilderAsync&lt;TParam0,TResult&gt;')[&gt;](IPipelineBuilderConditionInterfaceWithServiceProvider.TDelegate.TCondition.TResult..md 'DevUniverse.Pipelines.Core.Builders.Shared.Condition.ConditionInterface.IPipelineBuilderConditionInterfaceWithServiceProvider&lt;TDelegate,TCondition,TResult&gt;')  