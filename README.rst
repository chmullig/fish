Ever wanted to have animating fishes for progress bars in your command-line
script?

Ever thought about doing it but then realizing you have better things to do
with your time than to write meaningless ASCII animation programs?

Now you can have the best of both worlds: introducing ``fish``, the module that
makes any program look awesome and display useful data while churning away on
some good 'ole data.

Usage? Simple enough::

    >>> import fish
    >>> while churning:
    ...     churn_churn()
    ...     fish.animate()

Want to show the current record number?::

    >>> import fish
    >>> for i, x in enumerate(churning):
    ...     churn_churn()
    ...     fish.animate(amt=i)

Want to show numeric progress when you know the total number?::

    >>> import fish
    >>> f = fish.Fish(tot=len(data))
    >>> for i, datum in enumerate(data):
    ...     churn_churn()
    ...     f.animate(amt=i)

`See a demo on YouTube`__.

__ http://www.youtube.com/watch?v=tCoAPrO_fA0

The default fish is a simple bass at a pretty good velocity for an ASCII fish.

Possibilities are endless here, gentlemen:

    The only limit is yourself.

    -- zombo.com

`Fork on GitHub`__

__ http://github.com/lericson/fish
