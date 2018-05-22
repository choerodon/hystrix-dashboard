# hystrix-dashboard

Hystrix Dashboard is a dashboard for monitoring applications using Hystrix (https://github.com/Netflix/Hystrix). It is mainly used to monitor Hystrix's index information in real time. Information fed back through the interface can quickly discover problems in the system.

## Run via Maven

```bash
$ git clone https://github.com/choerodon/hystrix-dashboard.git
$ cd hystrix-dashboard
$ mvn clean spring-boot:run
```

Once running, open http://localhost:9001/hystrix-dashboard

## Documentation

> * Cluster via Turbine (default cluster): http://turbine-hostname:port/turbine.stream
> * Cluster via Turbine (custom cluster): http://turbine-hostname:port/turbine.stream?cluster=[clusterName]
> * Single Hystrix App: http://hystrix-app:port/hystrix.stream

The first two are for the cluster mode and the third is for the single node mode.

At the moment, we are using the first method.

For more details refer to https://github.com/Netflix-Skunkworks/hystrix-dashboard

## Reporting Issues
If you find any shortcomings or bugs, please describe them in the  [issue](https://github.com/choerodon/choerodon/issues/new?template=issue_template.md).

## How to Contribute
Pull requests are welcome! [Follow](https://github.com/choerodon/choerodon/blob/master/CONTRIBUTING.md) to know for more information on how to contribute.