### Garuda CRUD Generator
Garuda CRUD Generator is a CRUD Generator for Codeigniter Framework 3, Library Datatables Serverside to Display AdminLTE Data and Templates. The CRUD Generator that I use is Harviacode that has been modified so that the generic file results are in accordance with AdminLTE.

### Cara Install & Setup
1. Please clone or download this repository. 
2. Please extrack and rename the folder name to Garuda_crud_generator. 
3. create a new database with the name cigenerator then import the cigenerator.sql file. 
4. Open the web browser and enter http: // localhost / garuda_crud_generator / in the address bar.

### Login
To make the login process please use the following default account: <br/>
Email: admin@gmail.com<br/>
Password: password

## Features :

### 1. Dropdown Dynamic
This function is used to create dynamic dropdowns with data originating from the database, how to use:  :<br>
``` <?php echo cmb_dinamis(ElementName,TableName,FieldName,PrimaryKey,DefaultValue);?>```<br>
Example: : <br>
``` <?php echo datalist_dinamis('cmb_kelas','tbl_kelas','nama_kelas','id_kelas',5) ?>```

### 2. Datalist Dynamic
This function is used to create a dynamic datalist with data originating from the database, how to use: <br>
``` <?php echo datalist_dinamis(ElementName,TableName,FieldName,DefaultValue);?>```<br>
Example : <br>
``` <?php echo datalist_dinamis('ListUser','tbl_users','nama_lengkap') ?>```

### 3.Select Select Dynamic
This function is used to make dynamic select2 with data originating from the database, how to use: <br>
``` <?php echo select2_dinamis(ElementName,TableName,FieldName,PlaceHolder);?>```<br>
Example : <br>
``` <?php echo select2_dinamis('ListUser','tbl_users','nama_lengkap','Masukan Nama Users') ?>```

### Credit To : 
1.[Harviacode ](http://harviacode.com/) <br>
2.[AdminLTE](https://adminlte.io/)<br>
