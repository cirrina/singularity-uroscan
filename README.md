# singularity-uroscan
Includes specific (older) versions of bowtie, rsem, star etc, to use in ctg-rnaseq-uroscan pipeline. Does not include R and libraries used to generate the acutal report.



v1.0.1
 singularity exec --bind /projects/fs1/ /projects/fs1/shared/ctg-containers/rnaseq/singularity-uroscan-1.0.1.sif mamba list

███████████████/  /██/  /██/  /██/  /████████████████████████
              /  / \   / \   / \   / \  \____
             /  /   \_/   \_/   \_/   \    o \__,
            / _/                       \_____/  `
            |/
        ███╗   ███╗ █████╗ ███╗   ███╗██████╗  █████╗
        ████╗ ████║██╔══██╗████╗ ████║██╔══██╗██╔══██╗
        ██╔████╔██║███████║██╔████╔██║██████╔╝███████║
        ██║╚██╔╝██║██╔══██║██║╚██╔╝██║██╔══██╗██╔══██║
        ██║ ╚═╝ ██║██║  ██║██║ ╚═╝ ██║██████╔╝██║  ██║
        ╚═╝     ╚═╝╚═╝  ╚═╝╚═╝     ╚═╝╚═════╝ ╚═╝  ╚═╝

        mamba (0.15.3) supported by @QuantStack

        GitHub:  https://github.com/mamba-org/mamba
        Twitter: https://twitter.com/QuantStack

█████████████████████████████████████████████████████████████

# packages in environment at /opt/software/uroscan_env:
#
# Name                    Version                   Build  Channel
_libgcc_mutex             0.1                 conda_forge    conda-forge
_openmp_mutex             4.5                       1_gnu    conda-forge
_r-mutex                  1.0.1               anacondar_1    conda-forge
bioconductor-biobase      2.40.0           r341h470a237_0    bioconda
bioconductor-biocgenerics 0.26.0                   r341_0    bioconda
bioconductor-ebseq        1.20.0                   r341_0    bioconda
blas                      1.1                    openblas    conda-forge
boost                     1.64.0                   py36_4    conda-forge
boost-cpp                 1.64.0                        1    conda-forge
bowtie2                   2.3.3.1          py36pl5.22.0_0    bioconda
bzip2                     1.0.8                h7f98852_4    conda-forge
ca-certificates           2021.5.30            ha878542_0    conda-forge
cairo                     1.14.12           ha4e643d_1006    conda-forge
curl                      7.61.0               h93b3f91_2    conda-forge
fontconfig                2.13.1            hba837de_1005    conda-forge
freetype                  2.10.4               h0708190_1    conda-forge
gettext                   0.19.8.1          hf34092f_1004    conda-forge
glib                      2.58.3          py36hd3ed26a_1004    conda-forge
graphite2                 1.3.13            h58526e2_1001    conda-forge
gsl                       2.2.1           blas_openblashddceaf2_6    conda-forge
harfbuzz                  1.8.8                hffaf4a1_0
icu                       58.2              hf484d3e_1000    conda-forge
jbig                      2.1               h7f98852_2003    conda-forge
jemalloc                  5.2.1                h9c3ff4c_5    conda-forge
jpeg                      9d                   h36c2ea0_0    conda-forge
krb5                      1.14.6                        0    conda-forge
ldc                       1.13.0               h02c9852_1    conda-forge
lerc                      2.2.1                h9c3ff4c_0    conda-forge
libblas                   3.8.0               17_openblas    conda-forge
libboost                  1.67.0               h46d08c1_4
libcblas                  3.8.0               17_openblas    conda-forge
libdeflate                1.7                  h7f98852_5    conda-forge
libffi                    3.2.1             he1b5a44_1007    conda-forge
libgcc                    7.2.0                h69d50b8_2    conda-forge
libgcc-ng                 11.1.0               hc902ee8_8    conda-forge
libgfortran               3.0.0                         1    conda-forge
libgfortran-ng            7.5.0               h14aa051_19    conda-forge
libgfortran4              7.5.0               h14aa051_19    conda-forge
libgomp                   11.1.0               hc902ee8_8    conda-forge
libiconv                  1.16                 h516909a_0    conda-forge
liblapack                 3.8.0               17_openblas    conda-forge
libopenblas               0.3.10               h5a2b251_0
libpng                    1.6.37               h21135ba_2    conda-forge
libssh2                   1.8.0             h1ad7b7a_1003    conda-forge
libstdcxx-ng              11.1.0               h56837e0_8    conda-forge
libtiff                   4.3.0                hf544144_1    conda-forge
libuuid                   2.32.1            h7f98852_1000    conda-forge
libwebp-base              1.2.1                h7f98852_0    conda-forge
libxcb                    1.13              h7f98852_1003    conda-forge
libxml2                   2.9.12               h03d6c58_0
lz4-c                     1.9.3                h9c3ff4c_1    conda-forge
ncurses                   6.2                  h58526e2_4    conda-forge
numpy                     1.19.5           py36hfc0c790_2    conda-forge
openblas                  0.3.3             h9ac9557_1001    conda-forge
openssl                   1.0.2u               h516909a_0    conda-forge
pango                     1.40.14              he752989_2    conda-forge
pcre                      8.45                 h9c3ff4c_0    conda-forge
perl                      5.22.0.1                      0    conda-forge
perl-module-build         0.4224               pl5.22.0_0    bioconda
pip                       21.2.4             pyhd8ed1ab_0    conda-forge
pixman                    0.34.0            h14c3975_1003    conda-forge
pthread-stubs             0.4               h36c2ea0_1001    conda-forge
python                    3.6.7             hd21baee_1002    conda-forge
python_abi                3.6                     2_cp36m    conda-forge
r-assertthat              0.2.0            r341h6115d3f_1    conda-forge
r-base                    3.4.1                h4fe35fd_8    conda-forge
r-bibtex                  0.4.2            r341hc070d10_2    conda-forge
r-bitops                  1.0_6            r341hc070d10_2    conda-forge
r-blockmodeling           0.3.1            r341h364d78e_0    conda-forge
r-catools                 1.17.1.1         r341h9d2a408_2    conda-forge
r-cli                     1.0.0            r341h6115d3f_1    conda-forge
r-codetools               0.2_15           r341h6115d3f_1    conda-forge
r-crayon                  1.3.4            r341h6115d3f_1    conda-forge
r-digest                  0.6.18           r341hc070d10_0    conda-forge
r-doparallel              1.0.11           r341h6115d3f_1    conda-forge
r-dorng                   1.7.1            r341h6115d3f_0    conda-forge
r-foreach                 1.4.4            r341h6115d3f_1    conda-forge
r-gdata                   2.18.0           r341h6115d3f_1    conda-forge
r-glue                    1.3.0            r341h470a237_2    conda-forge
r-gplots                  3.0.1            r341h6115d3f_1    conda-forge
r-gtools                  3.8.1            r341hc070d10_2    conda-forge
r-iterators               1.0.10           r341h6115d3f_1    conda-forge
r-kernsmooth              2.23_15          r341h364d78e_2    conda-forge
r-lattice                 0.20_35          r341hc070d10_0    conda-forge
r-magrittr                1.5              r341h6115d3f_1    conda-forge
r-matrix                  1.2_14           r341hc070d10_2    conda-forge
r-pkgmaker                0.27             r341h6115d3f_0    conda-forge
r-praise                  1.0.0            r341h6115d3f_1    conda-forge
r-r6                      2.2.2            r341h6115d3f_1    conda-forge
r-registry                0.5              r341h6115d3f_1    conda-forge
r-rlang                   0.3.0.1          r341h470a237_0    conda-forge
r-rngtools                1.3.1            r341h6115d3f_1    conda-forge
r-stringi                 1.2.4            r341h9d2a408_1    conda-forge
r-stringr                 1.3.1            r341h6115d3f_1    conda-forge
r-testthat                2.0.1            r341h9d2a408_0    conda-forge
r-withr                   2.1.2            r341h6115d3f_0    conda-forge
r-xtable                  1.8_3                 r341_1000    conda-forge
readline                  7.0               hf8c457e_1001    conda-forge
rsem                      1.3.0               boost1.64_3    bioconda
salmon                    0.13.1               h86b0361_0    bioconda
sambamba                  0.6.8                h89e63da_2    bioconda
samtools                  1.3                           2    bioconda
setuptools                58.0.4           py36h5fab9bb_0    conda-forge
sqlite                    3.28.0               h8b20d00_0    conda-forge
star                      2.5.3a                        0    bioconda
tbb                       2021.3.0             h4bd325d_0    conda-forge
tk                        8.6.11               h27826a3_1    conda-forge
wheel                     0.37.0             pyhd8ed1ab_1    conda-forge
xorg-kbproto              1.0.7             h7f98852_1002    conda-forge
xorg-libice               1.0.10               h7f98852_0    conda-forge
xorg-libsm                1.2.3             hd9c2040_1000    conda-forge
xorg-libx11               1.7.2                h7f98852_0    conda-forge
xorg-libxau               1.0.9                h7f98852_0    conda-forge
xorg-libxdmcp             1.1.3                h7f98852_0    conda-forge
xorg-libxext              1.3.4                h7f98852_1    conda-forge
xorg-libxrender           0.9.10            h7f98852_1003    conda-forge
xorg-libxt                1.2.1                h7f98852_2    conda-forge
xorg-renderproto          0.11.1            h7f98852_1002    conda-forge
xorg-xextproto            7.3.0             h7f98852_1002    conda-forge
xorg-xproto               7.0.31            h7f98852_1007    conda-forge
xz                        5.2.5                h516909a_1    conda-forge
zlib                      1.2.11            h516909a_1010    conda-forge
zstd                      1.5.0                ha95c52a_0    conda-forge
