## 1.0.0

BACKWARDS INCOMPATIBILITIES / NOTES:

* Reworked to use the official ES 6 docker images. In order to avoid having to
manage plugins and geoip config at this time, only the files managed by this
role are mounted into the container.  Previously the entire `config` folder was
mounted.
