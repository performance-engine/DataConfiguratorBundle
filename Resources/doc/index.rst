Add kernel loading into AppKernel.php
	
	new PerformanceEngine\Bundle\DataConfiguratorBundle\PerformanceEngineDataConfiguratorBundle(),

Add route information

	PerformanceEngineDataConfiguratorBundle:
	resource: "@PerformanceEngineDataConfiguratorBundle/Controller/"
	type:     annotation
	prefix:   /data-configurator
