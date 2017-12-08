dygraphs / dpxdt
----------------

Screenshot testing for dygraphs. Should eventually make its way into the main dygraphs repo.

## Usage

Install [dpxdt] globally:

    pip install dpxdt
    
Then update the screenshots:

    dpxdt update .
    
You'll this repo and the `dygraphs` repo to be siblings for this to work, e.g.

    $HOME/
      git/
        dygraphs
        dygraphs-dpxdt

If nothing has changed, you'll see a clean `git diff`. If something has, you can inspect it using something like [`git webdiff`][webdiff].

[dpxdt]: https://github.com/bslatkin/dpxdt
[webdiff]: https://github.com/danvk/webdiff
