# RayTraceEllipsoid

[![Build Status](https://travis-ci.org/yakir12/RayTraceEllipsoid.jl.svg?branch=master)](https://travis-ci.org/yakir12/RayTraceEllipsoid.jl)

[![Coverage Status](https://coveralls.io/repos/yakir12/RayTraceEllipsoid.jl/badge.svg?branch=master&service=github)](https://coveralls.io/github/yakir12/RayTraceEllipsoid.jl?branch=master)

[![codecov.io](http://codecov.io/github/yakir12/RayTraceEllipsoid.jl/coverage.svg?branch=master)](http://codecov.io/github/yakir12/RayTraceEllipsoid.jl?branch=master)

This Julia package allows for geometric ray tracing with ellipsoids. It includes intersection and refraction/reflection of rays with arbitrary ellipsoids. It accomplishes that in about 100 lines of code thanks to heavy use of `CoordinateTransformations.jl` and `StaticArrays.jl`.