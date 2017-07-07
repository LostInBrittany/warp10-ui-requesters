# warp10-ui-requesters

| A set Polymer 2.x Web Components to call Warp 10 instances


## Elements

- [`warp10-ui-warpscript-caller`](https://github.com/cityzendata/warp10-ui-requesters/blob/master/warp10-ui-warpscript-caller.html):  Polymer 2.x Web Component to do single HTTP calls to Warp 10 instances


## Doc & demo

[https://cityzendata.github.io/warp10-ui-requesters](https://cityzendata.github.io/warp10-ui-requesters)


## Install

Install the component using [Bower](http://bower.io/):

```sh
$ bower install cityzendata/warp10-ui-requesters --save
```

Or [download as ZIP](https://github.com/cityzendata/warp10-ui-requesters/archive/gh-pages.zip).## Usage

1. Import Web Components' polyfill (if needed):

    ```html
    <script src="bower_components/webcomponentsjs/webcomponents.js"></script>
    ```

2. Import the Custom Elements you need from the collection:

    ```html
    <link rel="import" href="bower_components/warp10-ui-requesters/warp10-ui-warpscript-caller.html">
    ```

3. Start using them!

    ```html
        <warp10-ui-warpscript-caller
            url="https://warp.cityzendata.net/api/v0/exec"
            warpscript="NOW"
            reload="10"
            last-response="{{lastResponse}}"
            auto debug></warp10-ui-warpscript-caller>
    ```



## Contributing

1. Fork it!
2. Create your feature branch: `git checkout -b my-new-feature`
3. Commit your changes: `git commit -m 'Add some feature'`
4. Push to the branch: `git push origin my-new-feature`
5. Submit a pull request :D

## License

[Apache 2.0](http://opensource.org/licenses/Apache-2.0)
