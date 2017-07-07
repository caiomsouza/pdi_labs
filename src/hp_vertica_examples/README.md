# HP Vertica Example

This example explains how to use PDI and BA Server with HP Vertica.

# Install HP Vertica using Docker

Use the link below to install Vertica using docker:<BR>
https://github.com/caiomsouza/docker-vertica <BR>


# Best Practices - HP Vertica Integration with PDI Tips and Techniques
https://support.pentaho.com/hc/en-us/articles/206022303-Best-Practices-HP-Vertica-Integration-with-PDI-Tips-and-Techniques

# Example of how to create tables in HP Vertica

Samples below were based on this link: <BR>
https://my.vertica.com/docs/7.1.x/HTML/Content/Authoring/SQLReferenceManual/Statements/CREATETABLE.htm<BR>


```
CREATE TABLE t (a INT);
 CREATE TABLE
 
CREATE TABLE t (a INT, b VARCHAR(256));

CREATE TABLE IF NOT EXISTS t (a INT, b VARCHAR(256));
```

# Determining Your Version of HP Vertica
Samples below were based on this link: <BR>
https://my.vertica.com/docs/7.1.x/HTML/Content/Authoring/AdministratorsGuide/Diagnostics/DeterminingYourVersionOfHPVertica.htm <BR>

```
SELECT version();
```

# 
start-demo-vertica-docker-no-data-persistence.sh
```
sudo docker run -p 5433:5433  sumitchawla/vertica
```

# Run the command below
chmod +x start-demo-vertica-docker-no-data-persistence.sh

# Vertica Article
https://www.know-bi.be/blog/article/postgresql-vs.-vertica-time-is-money


# Vertica SQL Samples
```
CREATE TABLE t (a INT);

SELECT version();

DROP TABLE IF EXISTS vertica_db_control;
CREATE TABLE vertica_db_control (vertica_version VARCHAR(256));

SELECT * FROM vertica_db_control;

```

# Print screen 

![img1](https://raw.githubusercontent.com/caiomsouza/pdi_labs/master/src/hp_vertica_examples/img/BAServer_Connection_Example_With_HP_Vertica.PNG)

![img2](https://raw.githubusercontent.com/caiomsouza/pdi_labs/master/src/hp_vertica_examples/img/PDI_Connection_with_HP_Vertica.PNG)

![img3](https://raw.githubusercontent.com/caiomsouza/pdi_labs/master/src/hp_vertica_examples/img/PDI_Transformation_to_Connect_with_HP_Vertica_and_get_vertica_db_version.PNG)



