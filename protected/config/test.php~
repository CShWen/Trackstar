<?php

return CMap::mergeArray(
	require(dirname(__FILE__).'/main.php'),
	array(
		'components'=>array(
			'fixture'=>array(
				'class'=>'system.test.CDbFixtureManager',
			),
			'db'=>array(
				'connectionString' => 'mysql:host=localhost;dbname=trackstar_test',
				'emulatePrepare' => true,
				'username' => 'root',
				'password' => 'csw',
				'charset' => 'utf8',
			),
			'cache'=>array( 
			    'class'=>'system.caching.CFileCache', 
			    'cachePath'=> '/home/csw/phpws/trackstar/protected/runtime/test/',
			),
		),
	)
);
