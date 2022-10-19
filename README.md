# "Tirages" for MO/TO computers

This is a very basic program, written in BASIC language for the Thomson MO5 French computer.

> The program has a French UI only and will stay like that.

The project is aiming at demonstrate the use of the [moto-tools](https://github.com/sporniket/moto-tools) project. Look at [`reformat`](./reformat) and [`build`](./build) script files, that are then leveraged inside the github action script [`release.yml`](./.github/release.yml).

A release will be generate either when there is new things on the program itself —following the semver _Major.Minor.Fix_ numbering— ; or when there is a significant evolution of moto-tools, most likely when it changes the content of a delivery, the numbering will then be _Major.Minor.Fix.Delivery_.

## License

The program in itself is published under the GNU General Public License v3. The scripts demonstrating the use of moto-tools are public domain.

## What's new

### Version 0.0.1

* Initial release, the program implements "heads and tails".
* The release contains a tape archive for the MO5, containing an ASCII basic program. use `merge"tirages",r` to run the program.
