Polyglot opening book reading
=============================

.. autofunction:: chess.polyglot.open_reader

.. autoclass:: chess.polyglot.Entry
    :members:

    .. py:attribute:: key

        The Zobrist hash of the position.

    .. py:attribute:: raw_move

        The raw binary representation of the move. Use the `move()` method to
        extract a move object from this.

    .. py:attribute:: weight

        An integer value that can be used as the weight for this entry.

    .. py:attribute:: learn

        Another integer value that can be used for extra information.

.. autoclass:: chess.polyglot.Reader
    :members:

.. py:data:: chess.POLYGLOT_RANDOM_ARRAY
    :annotation: = [0x9D39247E33776D41, ..., 0xF8D626AAAF278509]

    Array of 781 polyglot compatible pseudo random values for Zobrist hashing.
