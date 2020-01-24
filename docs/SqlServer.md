#### sys.sysobjects

> Contains one row for each object that is created within a database, such as a constraint, default, log, rule, and stored procedure.

[More info] (https://docs.microsoft.com/en-us/sql/relational-databases/system-compatibility-views/sys-sysobjects-transact-sql?redirectedfrom=MSDN&view=sql-server-ver15)


xtype	char(2)	Object type. Can be one of the following object types:

AF = Aggregate function (CLR)

C = CHECK constraint

D = Default or DEFAULT constraint

F = FOREIGN KEY constraint

L = Log

FN = Scalar function

FS = Assembly (CLR) scalar-function

FT = Assembly (CLR) table-valued function

IF = In-lined table-function

IT = Internal table

P = Stored procedure

PC = Assembly (CLR) stored-procedure

PK = PRIMARY KEY constraint (type is K)

RF = Replication filter stored procedure

S = System table

SN = Synonym

SQ = Service queue

TA = Assembly (CLR) DML trigger

TF = Table function

TR = SQL DML Trigger

TT = Table type

U = User table

UQ = UNIQUE constraint (type is K)

V = View

X = Extended stored procedure

---------------------------------------------------------------------------------
