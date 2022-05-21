Gui
===



====================================== ============================================================================ ======================================
Method                                  Arguments                                                                    Return
====================================== ============================================================================ ======================================
beginWindow                             ``string`` name
text                                    ``string`` text
textColored                             ``string`` text, vector4 color
button                                  ``string`` label                                                            ``bool`` true if clicked
button                                  ``string`` label, ``vector2`` size                                          ``bool`` true if clicked
slider                                  ``string`` label, ``number`` value, ``number`` min, ``number`` max          ``number`` new value
input                                   ``string`` label, ``string`` value                                          ``string`` new value
input                                   ``string`` label, ``number`` value                                          ``number`` new value
sameLine
newLine
indent                                  ``number`` value
unindent                                ``number`` value
separator
getRegionAvail                                                                                                      ``vector2``
checkbox                                ``string`` label, ``bool`` value											``bool`` new value	
setNextWindowPos						``vector2`` position
setNextWindowSize						``vector2`` size
setNextWindowBgAlpha					``number`` value
setWindowFontScale						``number`` value
pushID									``string`` id
popID
beginFrame								``string`` id, ``vector2`` size
endFrame
endWindow
openPopup								``string`` id
beginPopup								``string`` id
beginPopupModal							``string`` id																``bool`` true if opened
endPopup
closeCurrentPopup
====================================== ============================================================================ ======================================