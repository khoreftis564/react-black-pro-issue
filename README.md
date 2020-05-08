# react-black-pro-issue

The issue I am seeing is when adding routes under a mutli-level collapse the activeRoute is picking up both children and showing them as active. 

Code below that is causing the issue

```
  activeRoute = routeName => {
    return this.props.location.pathname.indexOf(routeName) > -1 ? "active" : "";
  };
```
