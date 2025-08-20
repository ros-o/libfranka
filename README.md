# libfranka-fer: C++ library for the Franka Emika Panda Robot

Through this library, you can control the Franka Emika Panda robot with an enabled [Franka Control Interface (FCI)][fci-docs].

Note that Franka Robotics announced [End of Life for the panda robot](eol) at the end of 2023
and broke API support for the robot in the development version of libfranka [in 2022](api-incompatible).

This repository forked from the last version that supported the panda.

## License

`libfranka-fer` is licensed under the [Apache 2.0 license][apache-2.0].

[apache-2.0]: https://www.apache.org/licenses/LICENSE-2.0.html
[fci-docs]: https://frankarobotics.github.io/docs
[eol]: https://download.franka.de/End-of-Life-Franka-Emika-Robot_EN.pdf
[api-incompatible]: https://github.com/frankarobotics/libfranka/blob/d171cc99300a711631bd3c8362c9d66680d63a5c/CHANGELOG.md?plain=1#L81
