<p align="center">
  <a href="https://red4sec.com" target="_blank"><img src="https://github.com/Red4Sec/NEO-SmartVote/raw/master/Resources/NEO-smart-economy-logo.png" width="200px"></a>
</p>
<h1 align="center">
Smart Vote - Smart Contract Samples
</h1>

<p align="center">
 Used as example contract in different Workshops.
</p>

## Slides

* [CSharp Slides](https://github.com/Red4Sec/NEO-SmartVote/raw/master/Resources/NEO%20CSharp%20Workshop.pdf)
* [Python Slides](https://docs.google.com/presentation/d/1KP2IP0ndGuyqlYPuFkjRoci9EjQqUZESIpDMsF-05Qs)

## Problems with docker-compose?

*Solve error: ERROR: Version in "./docker-compose.yml" is unsupported*

Follwed below steps to upgrade docker-compose in ubuntu16.04

```
$which docker-compose
/usr/bin/docker-compose
$sudo rm /usr/bin/docker-compose
curl -L https://github.com/docker/compose/releases/download/1.20.0/docker-compose-`uname -s`-uname -m -o /usr/bin/docker-compose
chmod +x /usr/bin/docker-compose
```
