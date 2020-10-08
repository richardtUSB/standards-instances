# Instances

Within the Urban Observatory ontology we have defined various *Classes* (available [here](https://urbanobservatory.stoplight.io/docs/standards-namespace/docs/README.md)). For example we define an *ObservableProperty* class. The Urban Observatories will create multiple instances of each of these classes. Example instances for the *ObservableProperty* class could be *air-temperature* or *pm10-mass-concentration*. 

Because a lot of these instances will be used by more than one Observatory it makes sense to list common instances to ensure we all refer to the same definition. The last thing we want is one Urban Observatory using an instance called *air-temperature* and another called *temperature-of-the-air* with virtually the same definition. This would make it far more difficult for users to extract comparable data from several Observatories.

Our instances are defined in JSON files. Here's a link to instances for each class:

[Observable Properties](https://github.com/urbanobservatory/standards-instances/blob/master/instances/observable-properties.json)

[Disciplines](https://github.com/urbanobservatory/standards-instances/blob/master/instances/disciplines.json)

[Aggregations](https://github.com/urbanobservatory/standards-instances/blob/master/instances/aggregations.json)

[Features Of Interest](https://github.com/urbanobservatory/standards-instances/blob/master/instances/features-of-interest.json)

[Units](https://github.com/urbanobservatory/standards-instances/blob/master/instances/units.json)



