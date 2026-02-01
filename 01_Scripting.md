### GlideRecord
A sample text
- One test
- Two test

```var chg=new GlideRecord("change_request");
chg.query();
while(chg.next()){
gs.info("Change Number:"+chg.number);

}
gs.info("Row Count:"+chg.getRowCount());
```
