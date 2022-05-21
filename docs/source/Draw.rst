Draw
====

Methods

=============================== ============================================================================================================
Method                           Arguments
=============================== ============================================================================================================
line							 ``vector2`` p1, ``vector2`` p2, ``number`` color, ``number`` thickness
rect							 ``vector2`` p1, ``vector2`` p2, ``number`` color, ``number`` rounding, ``number`` thickness
rectFilled						 ``vector2`` p1, ``vector2`` p2, ``number`` color, ``number`` rounding
rectShadow						 ``vector2`` p1, ``vector2`` p2, ``number`` color, ``number`` rounding, ``number`` thickness
rectGradient				     ``vector2`` p1, ``vector2`` p2, ``number`` color1, ``number`` color2, ``number`` color3, ``number`` color4
triangle						 ``vector2`` p1, ``vector2`` p2, ``vector2`` p3, ``number`` col, ``number`` thickness
triangleFilled	                 ``vector2`` p1, ``vector2`` p2, ``vector2`` p3, ``number`` col
circle	                         ``vector2`` center, ``number`` radius, ``number`` col
circleFilled				     ``vector2`` center, ``number`` radius, ``number`` col
circleShadow	                 ``vector2`` center, ``number`` radius, ``number`` col, ``number`` thickness
text	                         ``vector2`` pos, ``number`` col, ``string`` text
blurFullscreen	                 ``number`` alpha
monochromeFullscreen	         ``number`` amount
chromaticAberrationFullscreen	 ``number`` amount
=============================== ============================================================================================================