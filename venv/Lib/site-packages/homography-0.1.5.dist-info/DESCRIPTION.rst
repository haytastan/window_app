Home-page: https://github.com/satellogic/homography
Author: Slava Kerner, Amit Aronovitch
Author-email: amit@satellogic.com
License: GPLv3
Description-Content-Type: UNKNOWN
Description: ===========
        homography_
        ===========
        
        |Build Status|_ |Coverage Status|
        
        library for 2d homographies
        
        The 3x3 homography transformation matrix for transformations in two
        dimensions is illustrated below.
        
        ::
        
            | x0 |   | a  b  c | | x |
            | y0 | = | d  e  f | | y |
            | z0 |   | g  h  1 | | 1 |
          
          x' = x0 / z0
          y' = y0 / z0
        
        For documentation, visit the homography_ project page
        
        .. _homography: https://satellogic.github.io/homography/
        
        .. |Build Status| image:: https://travis-ci.org/satellogic/homography.svg?branch=master
        	          :alt: Build Status
        .. _Build Status: https://travis-ci.org/satellogic/homography
        
        .. |Coverage Status| image:: https://satellogic.github.io/homography/coverage.svg
                             :alt: Coverage Status
        
Platform: UNKNOWN
Classifier: Development Status :: 4 - Beta
Classifier: Environment :: Console
Classifier: Intended Audience :: Science/Research
Classifier: Operating System :: OS Independent
Classifier: Programming Language :: Python
Classifier: Topic :: Software Development :: Libraries :: Python Modules
Classifier: Topic :: Utilities
