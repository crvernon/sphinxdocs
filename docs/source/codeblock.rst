codeblock how-to
================

.. code-block:: python


    def human_beans(soil_water_sunshine_air) -> str:
        """A writer is like a bean plant - he has his little day,
        and then gets stringy.  - E.B. White

        :param soil_water_sunshine_air:    Atoms with a preference
        :type soil_water_sunshine_air:     str

        :return:                           A Pythagorean theorem

        """

        a = range(len(soil_water_sunshine_air)-1, 1, -1)

        b = [soil_water_sunshine_air[i] for i in a if i%2 == 0]

        return ''.join(b).replace('z', ' ')


    # atoms with a preference
    soil_water_sunshine_air = "qvltuiopsczeaezeeavoaqhkznsanlaeecb"

    # a different Pythagorean theorem
    c = human_beans(soil_water_sunshine_air)
