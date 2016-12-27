/*
 * Copyright (c) 2014 CodeAndMagic
 * Cristian Vrabie, Evelina Vrabie
 *
 * This file is part of android-promise.
 * android-promise is free software: you can redistribute it and/or modify it
 * under the terms of the GNU Lesser General Public License as published by the
 * Free Software Foundation, either version 3 of the License,or (at your option)
 * any later version.
 *
 * android-promise is distributed in the hope that it will be useful,
 * but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY
 * or FITNESS FOR A PARTICULAR PURPOSE.
 * See the GNU Lesser General Public License for more details.
 *
 * You should have received a copy of the GNU Lesser General Public License
 * along with android-promise. If not, see <http://www.gnu.org/licenses/>.
 */

package org.codeandmagic.promise;

/**
 * Created by evelina on 05/03/2014.
 */
public interface Promises<Success>{

    <Success2> Promises<Success2> map(final Transformation<Success, Success2> transform);

    Promises<Success> onSuccess(Callback<Success> onSuccess);

    Promises<Success> onFailure(Callback<Throwable> onFailure);

    Promises<Success> runOnUiThread();
}
