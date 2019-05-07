# ![LOGO](logo.png) EtMDB REST API v1 **flow**ground Connector

## Description

A generated **flow**ground connector for the EtMDB REST API v1 API (version 1.0.0).

Generated from: https://api.apis.guru/v2/specs/etmdb.com/1.0.0/swagger.json<br/>
Generated at: 2019-05-07T17:40:26+03:00

## API Description

The Ethiopian Movie Database

## Authorization

Supported authorization schemes:
- OAuth2

For OAuth 2.0 you need to specify OAuth Client credentials as environment variables in the connector repository:
* `OAUTH_CLIENT_ID` - your OAuth client id
* `OAUTH_CLIENT_SECRET` - your OAuth client secret

## Actions

### Return cinema details search result

> Return cinema details search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{cinema_name}__: Used as a key word to search cinemas,<br/>
> <br/>
> For more details on how cinemas are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/cinema-list/-updated_date

*Tags:* `cinema-detail`

#### Input Parameters
* `cinema_name` - _required_

### Return cinema schedule search result

> Return cinema schedule search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{movie_title}__: Used as a key word to search movie cast<br/>
> * You can use both Amharic or English charset/font to search<br/>
> <br/>
> For more details about cinema schedule, check each cinema from the cinema list [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `cinema-schedule`

#### Input Parameters
* `movie_title` - _required_

### Return cinema schedule search result

> Return cinema schedule search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> __{param}__ argument can be<br/>
> * movie title<br/>
> * cinema name<br/>
> * cinema hall name or<br/>
> * cinema technology<br/>
> <br/>
> For more details about cinema schedule, check each cinema from the cinema list [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `cinema-schedule`

#### Input Parameters
* `param` - _required_

### Return cinema schedule and showtime search result

> Return cinema schedule and showtime search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> * __{movie_title}__: Used as a key word to search movie cast<br/>
> * You can use both Amharic or English charset/font to search<br/>
> <br/>
> For more details about cinema schedule showtime, check each cinema from the cinema list [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `cinema-shedule-showtime`

#### Input Parameters
* `movie_title` - _required_

### Return cinema schedule and showtime search result

> Return cinema schedule and showtime search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> __{param}__ argument can be<br/>
> * movie title<br/>
> * cinema name<br/>
> * cinema hall name<br/>
> * showtime starting date<br/>
> * showtime ending date or<br/>
> * cinema technology<br/>
> <br/>
> For more details about cinema schedule, check each cinema from the cinema list [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `cinema-shedule-showtime`

#### Input Parameters
* `param` - _required_

### Return cinema search result

> Return cinema search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{id}__: Used as a key to search cinemas,<br/>
> <br/>
> For more details on how cinemas are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/cinema-list/-updated_date

*Tags:* `cinema`

#### Input Parameters
* `id` - _required_

### Return company credits search result

> Return company credits search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{movie_title}__: Used as a key word to search company credits for the movie<br/>
> * You can use both Amharic or English charset/font to search<br/>
> <br/>
> For more details on how company credits are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `company-credits`

#### Input Parameters
* `movie_title` - _required_

### Return company credits search result

> Return company credits search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> __{param}__ argument can be<br/>
> * company name<br/>
> * movie title or<br/>
> * company credit description (such as production, cinematography, etc)<br/>
> <br/>
> For more details on how company credits are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/company-list/company_name

*Tags:* `company-credits`

#### Input Parameters
* `param` - _required_

### Return company search result

> Return company search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{company_name}__: Used as a key word to search companies,<br/>
> <br/>
> For more details on how companies are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/company-list/-updated_date

*Tags:* `company`

#### Input Parameters
* `company_name` - _required_

### Return filmography type search result

> Return filmography type search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{filmography_description}__: Used as a key word to search filmography types<br/>
> <br/>
> For more details on how filmography types are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `filmography-type`

#### Input Parameters
* `filmography_description` - _required_

### Return filmography search result

> Return filmography search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{movie_title}__: Used as a key word to search movies<br/>
> * You can use both Amharic or English charset/font to search<br/>
> <br/>
> For more details on how filmographies are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `filmography`

#### Input Parameters
* `movie_title` - _required_

### Return filmography search result

> Return filmography search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> __{param}__ argument can be<br/>
> * artist first name<br/>
> * artist last name<br/>
> * artist username<br/>
> * movie title or<br/>
> * filmography description (such as director, actor, producer, etc)<br/>
> <br/>
> For more details on how filmographies are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `filmography`

#### Input Parameters
* `param` - _required_

### Return genre type search result

> Return genre type search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{genre_description}__: Used as a key word to search genre types<br/>
> <br/>
> For more details on how genre types are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `genre-type`

#### Input Parameters
* `genre_description` - _required_

### Return movie genre search result

> Return movie genre search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{movie_title}__: Used as a key word to search movie genres<br/>
> * You can use both Amharic or English charset/font to search<br/>
> <br/>
> For more details on how movies are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `genre`

#### Input Parameters
* `movie_title` - _required_

### Return movie genre search result

> Return movie genre search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{movie_genre_type}__: Used as a key word to search movie genres<br/>
> <br/>
> For more details on how movies are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `genre`

#### Input Parameters
* `movie_genre_type` - _required_

### Return job details search result

> Return job details search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{job_title}__: Used as a key word to search jobs,<br/>
> <br/>
> For more details on how job are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/job-list/-updated_date

*Tags:* `job`

#### Input Parameters
* `job_title` - _required_

### Return job details search result

> Return job details search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{company_name}__: Used as a key word to search jobs,<br/>
> <br/>
> For more details on how job are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/job-list/-updated_date

*Tags:* `job`

#### Input Parameters
* `company_name` - _required_

### Return movie media search result

> Return movie media search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{movie_title}__: Used as a key word to search media for movies<br/>
> * You can use both Amharic or English charset/font to search<br/>
> <br/>
> For more details on how media is listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `media`

#### Input Parameters
* `movie_title` - _required_

### Return cast media search result

> Return cast media search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> __{user}__ argument can be<br/>
> * artist first name<br/>
> * artist last name<br/>
> * artist username<br/>
> <br/>
> For more details on how cast media is listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/cast-list/-updated_date

*Tags:* `media`

#### Input Parameters
* `user` - _required_

### Return movie cast search result

> Return movie cast search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{movie_title}__: Used as a key word to search movie cast<br/>
> * You can use both Amharic or English charset/font to search<br/>
> <br/>
> For more details on how movie casts are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `movie-cast`

#### Input Parameters
* `movie_title` - _required_

### Return movie cast search result

> Return movie cast search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> __{param}__ argument can be<br/>
> * artist first name<br/>
> * artist last name<br/>
> * artist username<br/>
> * movie title or<br/>
> * character name<br/>
> <br/>
> For more details on how movie casts are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `movie-cast`

#### Input Parameters
* `param` - _required_

### Return movie search result

> Return movie search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{movie_title}__: Used as a key word to search movies<br/>
> * You can use both Amharic or English charset/font to search<br/>
> <br/>
> For more details on how movies are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `movie`

#### Input Parameters
* `movie_title` - _required_

### Return news or article search result

> Return news or article search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{title}__: Used as a key word to search news and articles,<br/>
> <br/>
> For more details on how news & articles are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/news-list/-updated_date

*Tags:* `news`

#### Input Parameters
* `title` - _required_

### Return cast search result

> Return cast search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> __{param}__ argument can be<br/>
> * artist first name<br/>
> * artist last name<br/>
> * artist username<br/>
> <br/>
> For more details on how cast are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/cast-list/-updated_date

*Tags:* `people`

#### Input Parameters
* `user` - _required_

### Return showtime search result

> Return showtime search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> __{param}__ argument can be<br/>
> * show time or<br/>
> * day of the week [Mon=1, Tue=2, Wed=3, Thu=4, Fri=5, Sat=6, Sun=7]<br/>
> <br/>
> For more details about showtime, check each cinema from the cinema list [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movie-list/-updated_date

*Tags:* `showtime`

#### Input Parameters
* `param` - _required_

### Return watchlist search result

> Return watchlist search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> <br/>
> * __{movie_title}__: Used as a key word to search movies on watchlist<br/>
> * You can use both Amharic or English charset/font to search<br/>
> <br/>
> For more details on how watchlist are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movies/watchlist/id

*Tags:* `watchlist`

#### Input Parameters
* `movie_title` - _required_

### Return watchlist search result

> Return watchlist search result<br/>
> <br/>
> ### Response Class (Status 200)<br/>
> __{param}__ argument can be<br/>
> * artist first name<br/>
> * artist last name<br/>
> * artist username<br/>
> * movie title or<br/>
> <br/>
> For more details on how watchlist are listed [see here][ref].<br/>
> [ref]: https://etmdb.com/en/movies/watchlist/id

*Tags:* `watchlist`

#### Input Parameters
* `param` - _required_

## License

**flow**ground :- Telekom iPaaS / etmdb-com-connector<br/>
Copyright © 2019, [Deutsche Telekom AG](https://www.telekom.de)<br/>
contact: flowground@telekom.de

All files of this connector are licensed under the Apache 2.0 License. For details
see the file LICENSE on the toplevel directory.
