# Custom blocks
 This are sample custom handlebars blocks. 

## Usage
Install the latest version of wchtools-cli:
Windows: 
```python
npm install -g wchtools-cli 
```
Linux/Mac:
```python
sudo npm install -g wchtools-cli 
```
Make sure that you have initialized wchtools with your user and tenant API URL. You will be prompted for your user password when deploying to the tenant. For more information go to [wchtools documentation](https://github.com/ibm-wch/wchtools-cli/blob/master/README.md#getting-started)

Update all edited artifacts with
```python
 wchtools push -AvI 
```

Pull all the artifacts with           
```python
 wchtools -AvI --ready --draft --dir <your directory>
```
