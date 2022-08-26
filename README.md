# NgxChartsPoc

This project was generated with [Angular CLI](https://github.com/angular/angular-cli) version 13.3.9.

![image](https://user-images.githubusercontent.com/17774559/186968937-efef95a1-8ba0-44c9-be69-4421b86ab8f8.png)

## Startup

1. Run `yarn`
2. Run `yarn start`

## Package Size Analysis

To run the existing analysis you can run

- `yarn analyze:before` for the package sizes before adding ngx-charts
- `yarn analyze:after` for the package sizes after adding ngx-charts

Some images are below of those package sizes:

Before:

![image](https://user-images.githubusercontent.com/17774559/186968834-43a2cb08-bf05-4f93-a079-21c5f8e8bd2f.png)

After:

![image](https://user-images.githubusercontent.com/17774559/186968894-72e7de34-f777-42e8-b99a-c1d477f60cc9.png)

## Performance Analysis

`ngx-charts` doesn't seem to have any visible slowdown with a 6x speed CPU throttle

## Snapfactory (Custom Tool)

Rendering as a PDF didn't show the legend colors

![image](https://user-images.githubusercontent.com/17774559/186990146-1ee198f7-ef83-4df4-9a29-2d81f912036e.png)

Rendering as an image showed up fine though

![image](https://user-images.githubusercontent.com/17774559/186990192-a749e99c-ff8a-43e0-b6c0-f62d96ed915b.png)
