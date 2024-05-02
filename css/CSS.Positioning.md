Different types of positions of elements:
position: static :

        The position of the element is determined by the document flow (default)

position: relative :

        Position the element relative to where the element would be placed normally.
        That is, the last position of the element.
        Eg:
            position : relative;
            top : 20;

         This Will move the element downwards for 20px.
         With relative, the space occupied by the element previously won't be lost.
         It will still takes its place but changes it's position.

position: absolute :

        Position the element absolutely inside the nearest non-static ancestor element.

        Whenever, we position an element in absolute, it will move and position itself relative to its parent's position which is positioned as relative.
        That is, the parent element should be given the value,

                         position: relative;

                    and main element should have,
                         position : absolute;
                         top: 10;

position: fixed :

        Position the element on a fixed position on the screen. With respect to the viewport.

position: sticky :

        The element is placed normally in the document flow, but keeps an offset relative to its nearest scrolling ancestor.

                    eg: position;
                        top:20;(20 px from the top of view port)
                        z-index: 100;
                    If the nearest ancestor is main, then,
                        While scrolling, the element will move along but will stick to a position which is offset from the viewport.

Always give "top"or "bottom or "left or "right " = sum number either + or -, when using position attribute.

                        Always, give the attribute z-index: 100 (any high number to keep the elemnt on top of all other elements)
