# On AWS \(ECS\)

{% hint style="warn" %}
We do not currently support deployment on ECS.
{% endhint %}

The current iteration is not compatible with ECS. Airbyte currently relies on docker containers being able to create other docker containers. ECS does not permit containers to do this. We will be revising this strategy soon, so that we can be compatible with ECS and other container services.
