# benchmark.py results

Running benchmarks with size=5000, iterations=20...

Matrix Multiplication Time: 46.449672 seconds
Element-wise Addition Time: 1.128577 seconds
Reduction (Sum) Time: 0.185694 seconds

# numpy show_config() results

blas_armpl_info:
NOT AVAILABLE
blas_mkl_info:
NOT AVAILABLE
blis_info:
NOT AVAILABLE
openblas_info:
libraries = ['openblas', 'openblas']
library_dirs = ['/usr/lib/s390x-linux-gnu']
language = c
define_macros = [('HAVE_CBLAS', None)]
blas_opt_info:
libraries = ['openblas', 'openblas']
library_dirs = ['/usr/lib/s390x-linux-gnu']
language = c
define_macros = [('HAVE_CBLAS', None)]
lapack_armpl_info:
NOT AVAILABLE
lapack_mkl_info:
NOT AVAILABLE
openblas_lapack_info:
libraries = ['openblas', 'openblas']
library_dirs = ['/usr/lib/s390x-linux-gnu']
language = c
define_macros = [('HAVE_CBLAS', None)]
lapack_opt_info:
libraries = ['openblas', 'openblas']
library_dirs = ['/usr/lib/s390x-linux-gnu']
language = c
define_macros = [('HAVE_CBLAS', None)]
Supported SIMD extensions in this NumPy install:
baseline =
found = VX,VXE,VXE2
not found =
None

# lscpu

Architecture: s390x
CPU op-mode(s): 32-bit, 64-bit
Byte Order: Big Endian
CPU(s): 2
On-line CPU(s) list: 0,1
Vendor ID: IBM/S390
Machine type: 8561
Thread(s) per core: 1
Core(s) per socket: 1
Socket(s) per book: 1
Book(s) per drawer: 1
Drawer(s): 2
CPU dynamic MHz: 5200
CPU static MHz: 5200
BogoMIPS: 3241.00
Dispatching mode: horizontal
Flags: esan3 zarch stfle msa ldisp eimm dfp edat etf3eh highgprs te vx vxd vxe gs vxe2 vxp sort dflt sie
Virtualization features:
Hypervisor: z/VM 7.3.0
Hypervisor vendor: IBM
Virtualization type: full
Caches (sum of all):
L1d: 256 KiB (2 instances)
L1i: 256 KiB (2 instances)
L2d: 8 MiB (2 instances)
L2i: 8 MiB (2 instances)
L3: 256 MiB
L4: 960 MiB
NUMA:
NUMA node(s): 1
NUMA node0 CPU(s): 0,1
Vulnerabilities:
Itlb multihit: Not affected
L1tf: Not affected
Mds: Not affected
Meltdown: Not affected
Mmio stale data: Not affected
Retbleed: Not affected
Spec store bypass: Not affected
Spectre v1: Mitigation; \_\_user pointer sanitization
Spectre v2: Mitigation; etokens
Srbds: Not affected
Tsx async abort: Not affected
