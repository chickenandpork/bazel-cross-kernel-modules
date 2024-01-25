# bazel-cross-kernel-modules
I need some kernel modules for my NAS.  I hate bit-rotting build systems, or some that have a whole lot of assumptions.  Let's use Bazel, and some common rules to fetch and leverage a vendor toolchain to build some modules.  Maybe it'll work and be extensible.
