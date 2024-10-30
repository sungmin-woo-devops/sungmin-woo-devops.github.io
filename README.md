### sungmin-woo.devops.github.io

Jekyll Garden v 0.4 powerd

> **Note**:-
> 
> This container is built upon on alpine based ruby image. There's an official Jekyll image available in docker hub which only support `amd64` images. You can opt to use that if you are running the container on an 64bit PC. If you want to run this on an ARM based system like Raspberry Pi, this would be a better option.
>
> The directories which will be frequently modified, are mapped as local volumes so that any changes made to those will be immediately picked up by the server and built. If you fancy changing content in other folders regularly, feel free to add them to the `volumes` section in `docker-compose.yml` before deploying.


## License

The theme is available as open source under the terms of the [MIT License](http://opensource.org/licenses/MIT).
