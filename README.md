# StudentIndicator-AWS-CICD

## 1. Setup Environment
Step 1:

```python
virtualenv venvStud -p python3.9
```

Step 2:

```python
source venvStud/bin/activate
```

## 2. Copy the project
```python
artifacts
src
templates
app.py
requirements.txt  # uncomment -e .
setup.py  # change your project name 
```

## 3. Run `requiremnts.txt`

## 4. Create `.ebextensions/python.config` for AWS

```python
mkdir .ebextensions
touch .ebextensions/python.config
```
Vist: [docu](https://docs.aws.amazon.com/elasticbeanstalk/latest/dg/create-deploy-python-container.html)

## 5. Create `application.py` by copy `app.py`

```python
touch application.py
```

